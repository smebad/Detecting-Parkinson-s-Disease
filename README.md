# 🧠 Detecting Parkinson's Disease using SVM 

## 📂 Dataset  
**Dataset Name:** [Parkinson’s Disease Data Set](https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set)  
**Description:**  
This dataset includes various acoustic measurements from voice recordings of individuals. The target variable (`status`) indicates whether the individual has Parkinson's disease (`1`) or not (`0`).

---

## 📝 Project Objectives  
1. Analyze and preprocess the dataset.  
2. Build a predictive model using **Support Vector Machine (SVM)**.  
3. Evaluate the model using **ROC AUC** for robust performance assessment.  
4. Develop a simple prediction system for new inputs.  

---

## 📊 Exploratory Data Analysis (EDA)  
Key observations from EDA:  
- The dataset contains 195 samples and 24 features.  
- **No missing values** were found.  
- There is a slight class imbalance, with more individuals diagnosed with Parkinson's disease.  
- Acoustic features, such as `MDVP:Fo(Hz)` and `PPE`, show distinct separations between classes.  

### 🔑 Key Visualizations  
- **Feature Distributions:** Identified skewed distributions and wide ranges.  
- **Heatmap:** Highlighted correlations among acoustic features.  
- **Pairplot:** Visualized class separability in feature space.

---

## ⚙️ Why SVM? 🤔  
Support Vector Machines (SVM) were chosen because:  
- **Effective for Small Datasets:** SVM performs well on datasets like this with fewer samples (195 observations).  
- **Robust to High Dimensionality:** The dataset contains 22 numerical features, making SVM ideal for handling such dimensions.  
- **Non-linear Classification:** By using the RBF kernel, SVM can capture complex patterns in the data.  

---

## 🧪 Model Evaluation  
The model was evaluated using several metrics:  

| Metric            | Score         |  
|--------------------|---------------|  
| **Accuracy**       | 89.74%        |  
| **ROC AUC Score**  | 0.848         |  

### 🔍 Why ROC AUC?  
- **Class Imbalance:** The ROC AUC metric provides a balanced view of model performance, especially with imbalanced data.  
- **Threshold Analysis:** It helps visualize the trade-off between sensitivity and specificity.  

### 📈 ROC Curve  
The ROC curve demonstrated strong model performance with an AUC of **0.848**, indicating the model's ability to differentiate between the two classes effectively.

---

## 🛠️ Simple Prediction System  
A lightweight system was built to predict whether a new individual has Parkinson's disease. Input features are preprocessed and passed to the trained SVM model for classification.  

---

## 🏆 Summary  
1. **Analysis:** Key features were explored to understand their relationship with Parkinson's disease.  
2. **Modeling:** SVM was used for its ability to handle high-dimensional data and achieve robust classification.  
3. **Evaluation:** The model showed strong performance with high accuracy and ROC AUC.  
4. **Deployment:** A prediction system was implemented to classify new data points.  

---

## 🔗 Links  
📂 [Dataset on Kaggle](https://www.kaggle.com/datasets/vikasukani/parkinsons-disease-data-set)  
👨‍💻 [GitHub Profile](https://github.com/smebad)  
📧 [Email me](mailto:mohammadebad1@hotmail.com)  

## 📣 Call to Action  
Feel free to clone this repository and enhance the model. If you have suggestions or improvements, [reach out to me](mailto:mohammadebad1@hotmail.com). Let's make machine learning impactful! 🌟

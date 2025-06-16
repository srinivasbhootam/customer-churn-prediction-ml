# 📊 Customer Churn Prediction: Logistic Regression, k-NN, and Decision Tree

This project analyzes the Telco Customer Churn dataset to predict customer churn using three supervised machine learning models: Logistic Regression, k-Nearest Neighbors (k-NN), and Decision Tree.

The goal is to help telecom companies proactively identify customers likely to churn and take appropriate retention measures.

---

## 📁 Dataset

The dataset used is `Telco-Customer-Churn.csv`, which contains 7,043 records with customer demographics, subscription details, contract types, billing information, and a churn indicator (`Yes` or `No`).

---

## 🔍 Project Workflow

1. **Data Cleaning & Preprocessing**  
   - Handling missing and inconsistent values  
   - Label encoding for categorical variables  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of churn  
   - Relationship between tenure, contract type, and monthly charges  

3. **Feature Scaling**  
   - Applied standardization for numerical features to improve model performance  

4. **Model Training**  
   - Logistic Regression  
   - k-Nearest Neighbors (k-NN)  
   - Decision Tree  

5. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-Score  
   - Confusion matrices and visual comparisons  

6. **Visual Summary**  
   - APA-style figures with clear figure numbers and captions  
   - Includes histograms, correlation heatmaps, F1-score comparisons, and confusion matrices

---

## 📊 Models Used

- **Logistic Regression** – Efficient, interpretable model best for balanced classification.  
- **k-Nearest Neighbors (k-NN)** – Simple algorithm, sensitive to data scaling and imbalance.  
- **Decision Tree Classifier** – Offers better recall, interpretable but prone to overfitting.

---

## ✅ Results

| Model              | Accuracy | F1-Score | Precision | Recall |
|-------------------|----------|----------|-----------|--------|
| Logistic Regression | 79%      | 0.55     | 0.62      | 0.49   |
| k-NN                | 74%      | 0.51     | 0.51      | 0.51   |
| Decision Tree       | 72%      | 0.50     | 0.48      | 0.52   |

- **Logistic Regression** showed the most balanced performance and lowest misclassification rate.
- **k-NN** struggled with class imbalance and was sensitive to feature scaling.
- **Decision Tree** offered better recall, which could be useful for catching more churn cases but had lower precision.

---

## 📌 Model Comparison

- Logistic Regression provided the best overall balance between recall and precision.
- Decision Tree achieved slightly better recall, making it suitable where missing a churner is more costly than a false alarm.
- k-NN, although simple, was less effective on this dataset due to sensitivity to outliers and class imbalance.

---

## 💼 Business Insights

- Customers on **month-to-month contracts** and those with **higher monthly charges** showed higher churn rates.
- Targeting these segments with loyalty programs or personalized offers could reduce churn.
- Using predictive modeling helps telecom providers take **proactive steps** to retain valuable customers before they leave.

---



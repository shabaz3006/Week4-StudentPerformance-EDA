# Week 4 Project: Predicting Employee Attrition using Machine Learning

## 📌 Project Overview
This project uses the IBM HR Analytics Employee Attrition dataset to predict whether an employee is likely to leave the company. It applies machine learning models to analyze key features affecting employee attrition.

## 🔧 Steps Followed

1. **Load Dataset**  
   Loaded IBM HR Analytics data and explored the structure.

2. **EDA (Exploratory Data Analysis)**  
   - Checked missing values and class distribution.  
   - Visualized key features like Age, JobRole, MonthlyIncome, etc.

3. **Data Preprocessing**  
   - Encoded categorical features using OneHotEncoder.  
   - Scaled numerical features using StandardScaler.  
   - Balanced the dataset using SMOTE.

4. **Model Training**  
   Trained multiple models like Logistic Regression, Decision Tree, and Random Forest.

5. **Model Evaluation**  
   Evaluated models using accuracy, precision, recall, and F1-score.

6. **Feature Importance**  
   Used Random Forest to identify most important features for attrition prediction.

## 📊 Tools & Libraries
- Python, pandas, matplotlib, seaborn
- scikit-learn
- imbalanced-learn (SMOTE)

## ✅ Final Output
Achieved good performance using Random Forest. Key influencing features include JobRole, Age, MonthlyIncome, and WorkLifeBalance.

---


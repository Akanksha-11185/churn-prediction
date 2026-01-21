# 📊 Customer Churn Prediction System

## 🔍 Project Overview
This project builds an end-to-end **Customer Churn Prediction System** using machine learning.
The goal is to identify customers who are likely to leave a telecom service so that proactive
retention strategies can be applied.

The project follows a complete data science pipeline:
data ingestion → analysis → feature engineering → modeling → business insights.

---

## 📁 Dataset
- **Source:** IBM Telco Customer Churn Dataset (Kaggle)
- **Rows:** ~7,000 customers
- **Target Variable:** `Churn` (Yes / No)

Each row represents a customer with demographic, service, and billing information.

---

## 🛠️ Tools & Technologies
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Git & GitHub**

---

## 🔬 Methodology

### 1. Data Loading & Cleaning
- Loaded raw customer data
- Identified and fixed data quality issues
- Converted non-numeric columns (`TotalCharges`) correctly

### 2. Exploratory Data Analysis (EDA)
- Analyzed churn patterns across tenure, contract type, and charges
- Visualized key relationships
- Identified major churn drivers

### 3. Feature Engineering
- Removed non-informative columns
- Encoded categorical variables
- Scaled numerical features
- Prepared model-ready datasets

### 4. Model Training
- Logistic Regression (baseline model)
- Random Forest Classifier (final model)
- Used train-test split with stratification

### 5. Model Evaluation
- Confusion Matrix
- Precision, Recall, F1-score
- ROC Curve and AUC Score

---

## 📈 Model Performance
- **Best Model:** Random Forest Classifier
- **ROC-AUC Score:** ~X.XX  
- **Recall (Churn Class):** High priority metric for business use

The model effectively identifies high-risk churn customers.

---

## 💡 Key Business Insights
- Customers with **short tenure** are significantly more likely to churn
- **Month-to-month contracts** show the highest churn rates
- Higher **monthly charges** are associated with increased churn risk

---

## 📌 Business Recommendations
- Target high-risk customers with early retention offers
- Encourage long-term contracts for new users
- Use churn probability to prioritize customer outreach

---

## 📂 Project Structure

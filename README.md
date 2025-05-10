# Customer Churn Prediction – AI for Marketing 📉🧠

This project uses machine learning to predict customer churn by analyzing demographic, behavioral, and account-related features. The aim is to help businesses proactively retain customers by identifying those at high risk of leaving.

## 📌 Objective

Customer churn is a major business concern, directly impacting revenue and long-term growth. This project leverages a **Random Forest classifier** to predict churn using historical customer data, enabling businesses to:

- Identify at-risk customers
- Develop targeted retention strategies
- Allocate resources more effectively

---

## 📊 Dataset Overview

The dataset includes comprehensive customer-level features:

### 🎯 Target Variable
- `Attrition_Flag`: Indicates whether the customer has churned or not.

### 🧾 Key Features
- `Customer_Age`, `Gender`, `Dependent_count`
- `Education_Level`, `Marital_Status`, `Income_Category`, `Card_Category`
- `Credit_Limit`, `Total_Revolving_Bal`, `Avg_Open_To_Buy`, `Avg_Utilization_Ratio`
- `Months_on_book`, `Total_Relationship_Count`
- `Total_Trans_Amt`, `Total_Trans_Ct`, `Total_Amt_Chng_Q4_Q1`, `Total_Ct_Chng_Q4_Q1`
- `Months_Inactive_12_mon`, `Contacts_Count_12_mon`

---

## 🔍 Exploratory Data Analysis (EDA)

- Identified patterns in customer age, gender, and credit usage
- Analyzed relationships between credit limit, transaction behavior, and churn
- Visualized feature distributions and correlations
- Noted skewed income distribution and inactivity trends

---

## 🧠 Machine Learning Pipeline

### ✅ Feature Engineering
- One-hot encoding for categorical variables
- Standardization of numerical variables

### 🔬 Feature Selection
- Used Chi-squared and T-tests to select the most predictive features

### 🤖 Model: Random Forest Classifier
- Chosen for its robustness and ability to handle mixed data types

### ⚙️ Hyperparameter Tuning
- Performed with `GridSearchCV` for optimal model performance

### 📈 Results
- Achieved **95.5% accuracy**
- Strong ability to detect non-churners and good performance for identifying churners

---

## 💼 Business Impact

- **Targeted Retention**: Personalize offers and communication for at-risk customers
- **Resource Efficiency**: Allocate marketing and customer success efforts to where they matter most
- **Continuous Learning**: Model can evolve with customer behavior over time

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/Mariee03/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Launch the notebook:
```bash
jupyter notebook churn_prediction.ipynb
```

## 📬 Author

Created by Marie Elyse Bassil
Feel free to explore, fork, or reach out!


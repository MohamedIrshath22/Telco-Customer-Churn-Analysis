# Telco-Customer-Churn-Analysis
A complete end-to-end business analyst project to explore and visualize customer churn patterns for a telecom company. This project helps identify key churn drivers and provides actionable insights for improving customer retention.

---

## 🔍 Problem Statement

Customer churn is a major concern in the telecom industry. The goal of this project is to:
- Understand what factors lead to customer churn
- Identify which customer segments are at highest risk
- Visualize churn metrics through an interactive Power BI dashboard

---

## 🛠️ Tools & Technologies

- **Python** (pandas, seaborn) – data cleaning & exploratory analysis  
- **Power BI** – dashboard creation & data visualization  
- **DAX** – custom metrics and calculated columns  
- **GitHub** – version control & portfolio hosting

---

## 📁 Dataset

- **Name:** Telco Customer Churn
- **Source:** [Kaggle - Telco Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Size:** ~7,000 customer records
- **Features:** customer demographics, contract types, internet service, payment methods, churn status, etc.

---

## 🧹 Data Cleaning (Python)

Performed with pandas:
- Removed duplicates and missing values
- Converted `TotalCharges` to numeric
- Transformed boolean/dummy variables for contract types and other fields

> 💾 Cleaned file: `Telco-Customer-Churn-Cleaned.csv`

---

## 📊 Dashboard Features (Power BI)

- **Overall Churn Rate**
- **Churn Rate by Contract Type** (Month-to-Month, One-Year, Two-Year)
- **Churn by Internet Service**
- **Churn by Payment Method**
- **Churn Distribution by Tenure**
- Filters by gender, senior citizen, and partner/dependents

## 📈 Key Insights

- 📉 Customers with **Month-to-Month contracts** are **most likely to churn** (43.5%)
- 🧾 **Electronic check** payments are linked to higher churn
- ⏳ Customers with **shorter tenure** churn more frequently
- 🛡️ Two-year contract holders are **least likely to churn** (2.8%)

  🙋‍♂️ Author
  Mohamed Irshath N 
📬 Email: mohamedirshath.nmi@gmail.com

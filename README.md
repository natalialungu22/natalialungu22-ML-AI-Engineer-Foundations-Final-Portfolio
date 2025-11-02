# 📊 Predicting Customer Churn — Telco Customer Churn Project

## 📌 Overview
This project is part of the **Machine Learning/AI Engineer Foundations** portfolio. The goal is
to analyze and predict customer churn for a telecommunications company using a real business
dataset from Kaggle.

Reducing churn is critical in subscription-based industries where retaining customers is
more cost-effective than acquiring new ones. This project demonstrates a complete end-to-end
machine learning workflow:

- Data Cleaning ✅
- Exploratory Data Analysis ✅
- Feature Engineering ✅
- Machine Learning Model ✅
- Business Insights ✅

---

## 🎯 Objectives
- Predict which customers are likely to churn
- Identify the most important churn risk factors
- Provide data-driven business recommendations
- Showcase ML and data analytics skills in a portfolio-ready project

---

## 📊 Dataset
**Source:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn
**Rows:** 7,043 customers  
**Columns:** 21 customer, service, and billing attributes  

Examples of predictor variables:

| Feature | Description |
|--------|-------------|
| `tenure` | Months with the company |
| `MonthlyCharges` | Monthly bill amount |
| `InternetService` | DSL / Fiber optic / None |
| `PaymentMethod` | Electronic check, credit card, etc. |
| `Partner`, `Dependents` | Customer family context |
| `Contract` | Month-to-month, one-year, two-year |
| `Churn` | Target label — Yes or No |

---

## 🧠 Machine Learning Workflow

1️⃣ Load and inspect data  
2️⃣ Clean missing and incorrect values  
3️⃣ Convert categorical variables → numeric (one-hot encoding)  
4️⃣ Split into training/testing sets  
5️⃣ Train a **Logistic Regression** model  
6️⃣ Evaluate performance on unseen data  
7️⃣ Communicate insights with business value

---

## 🔍 Key EDA Insights

Customers are more likely to churn if they:
- Have **month-to-month contracts**
- Use **fiber optic** internet services
- Pay by **electronic check**
- Have **lower tenure** (newer customers)
- Have **no partner** and **no dependents**

👉 These customers should be prioritized for retention efforts.

---

## 🤖 Model Performance

| Metric | Result |
|--------|-------|
| Accuracy | ~79% |
| Recall for Churn | 52% |
| Confusion Matrix |

✅ Strong baseline  
⚠ Model misses some churners → improvement opportunity

---

## 💡 Business Recommendations

To reduce churn, the telecom company should:
- Offer **long-term contract upgrades** for new customers
- Improve satisfaction for **fiber optic** users
- Encourage **automatic payment methods**
- Target **young, single** customers with loyalty/discount programs  
- Provide retention support earlier in the customer lifecycle

These actions can improve customer lifetime value and revenue retention.

---

## 🛠️ Tools & Technologies
- Python (Jupyter Notebook)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Logistic Regression)
- Git & GitHub




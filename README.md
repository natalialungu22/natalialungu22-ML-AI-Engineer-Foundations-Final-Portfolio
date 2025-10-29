# Predicting Customer Churn — Telco Customer Churn Dataset

## 📌 Overview  
This project is part of the **Machine Learning/AI Engineer Foundations** portfolio.  
The objective is to prepare a business-analytics dataset for machine learning modelling, explore the data, build a predictive model, and derive actionable insights for customer retention in a telecommunications company.

## 🎯 Project Scope  
### ✅ Goals  
- Predict which customers are likely to churn (i.e., leave the company)  
- Identify key drivers of churn to inform retention strategies  
- Demonstrate data-preparation, analysis, and modelling skills in an ML workflow  

### 📊 Data  
- **Dataset:** Telco Customer Churn Dataset  
- **Source:** Kaggle – [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Format:** CSV  
- **Description:** Customer account information for a telecom operator, including demographic, usage and account-service attributes, with a target variable `Churn` indicating whether the customer left.  

Some of the variables include:  
| Column | Description |
|--------|-------------|
| `customerID` | Unique customer identifier |
| `gender` | Male/Female |
| `SeniorCitizen` | 0 = No, 1 = Yes |
| `Partner` | Whether the customer has a partner |
| `tenure` | Number of months the customer has been with the company |
| `MonthlyCharges` | Customer’s monthly bill |
| `TotalCharges` | The total amount charged to the customer |
| `Churn` | Target: Yes/No |

### 🔍 Analysis Plan 
1. Load and inspect the dataset (shape, types, first rows)
2. Identify missing values and fix incorrect or inconsistent data
3. Explore the data using summary statistics and visualizations
4. Prepare the dataset for machine learning:
   - Encode categorical columns as numbers
   - Scale numeric columns if needed
5. Train **one simple baseline model** (Logistic Regression)
6. Review results and summarize what we learned


*Scope may evolve as insights emerge during the project.*

## 🛠️ Tools & Technologies  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  
- Git & GitHub  



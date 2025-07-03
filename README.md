
# 📊 Customer Churn Analysis

This project analyzes customer churn behavior using a telecom dataset. It investigates key factors such as payment methods, streaming services, contract types, and demographics that influence whether a customer stays or leaves.

---

## Problem Statement ##
Telecom companies face significant revenue loss due to customer churn, especially in competitive markets. However, without a deep understanding of the factors contributing to churn—such as payment methods, contract types, service usage, and customer demographics—it becomes difficult to implement effective retention strategies.

This project aims to analyze a telecom dataset to identify the key drivers of customer churn. By using data cleaning in Python and visualization in Power BI, the goal is to uncover patterns and correlations that can help reduce churn and improve customer satisfaction.
## 🔍 Project Overview

Customer churn is a key metric in subscription-based businesses. Understanding what influences churn helps improve retention strategies.

This project:
- Performs data cleaning and exploration using Python/Power BI
- Builds a clean and interactive Power BI dashboard
- Highlights trends and correlations in churn behavior

---

## 📁 Dataset Information

- Rows: 7043  
- Columns: 21  
- Source: Simulated telecom data  
- Target Variable: Churn (Yes/No)

---

## ⚙️ Key Fields Used

- Churn, gender, SeniorCitizen, Contract, PaymentMethod  
- MonthlyCharges, TotalCharges, tenure, StreamingTV, StreamingMovies  
- MultipleLines, InternetService

---

## 🧹 Data Cleaning Summary (Python – Pandas + NumPy)

Before building the dashboard, the dataset was cleaned using Python. Here's how the data was prepared for analysis:

1. Library Import  
   - Used pandas for data manipulation  
   - Used numpy for numerical operations

2. Data Loading  
   - Loaded the dataset using pd.read_csv() from a local directory

3. Initial Inspection  
   - Used .info() to check data types and null values  
   - Identified that TotalCharges had incorrect data types and blank spaces

4. Fixing Data Issues  
   - Replaced blank strings in TotalCharges with 0  
   - Converted TotalCharges to float for accurate numeric analysis

5. Verified Changes  
   - Rechecked the data types using .info() to confirm successful cleaning

📌 These preprocessing steps helped ensure smooth dashboard integration in Power BI and accurate insights.

---

## 📊 Dashboard Visuals

![Dashboard Screenshot](https://github.com/vaibhavkatwe17/Customer_Churn_Data_Analytics/blob/main/Chusomer%20churn%20Dashbord%20ss.jpg?raw=true)

### Key Visuals:
- Bar chart: Count of churned vs non-churned customers  
- Gender-wise and senior citizen-wise churn  
- StreamingTV & StreamingMovies impact  
- Payment method analysis  
- MultipleLines vs churn  
- Pie chart showing overall churn rate  
- KPI Cards (total revenue, tenure, customer count)

---

## 📈 Insights from Dashboard

- Churn Rate: ~27% of customers have churned
- High churn among:  
  - Senior citizens  
  - Month-to-month contract holders  
  - Customers using electronic check
- Lower churn:  
  - Annual or 2-year contracts  
  - Auto-payment methods like bank transfers or credit cards
- Streaming services have a mild correlation with churn  
- Customers without phone/internet service churn less

---

## 🧰 Tools & Tech Used

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard building & visualization |
| Python (Pandas) | Data cleaning & initial analysis |
| GitHub | Portfolio project hosting |
| Excel | Quick previews |

---

## 📌 Conclusion

This project demonstrates how business intelligence tools like Power BI can uncover actionable insights from telecom churn data. It emphasizes the importance of customer demographics, payment methods, and service types in predicting churn.

---

✅ Project by [Vaibhav Katwe](https://github.com/vaibhavkatwe17)

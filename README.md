# 📊 Customer Churn Analysis Dashboard – Power BI Project

This project analyzes customer churn behavior using a telecom dataset. It investigates key factors such as payment methods, streaming services, contract types, and demographics that influence whether a customer stays or leaves.

---

## 🔍 Project Overview

Customer churn is a key metric in subscription-based businesses. Understanding what influences churn helps improve retention strategies.

This project:
- Performs data cleaning and exploration using Python/Power BI
- Builds a clean and interactive Power BI dashboard
- Highlights trends and correlations in churn behavior

---

## 📁 Dataset Information

- **Rows**: 7043
- **Columns**: 21
- **Source**: Simulated telecom data
- **Target Variable**: `Churn` (Yes/No)

---

## ⚙️ Key Fields Used

- `Churn`, `gender`, `SeniorCitizen`, `Contract`, `PaymentMethod`
- `MonthlyCharges`, `TotalCharges`, `tenure`, `StreamingTV`, `StreamingMovies`
- `MultipleLines`, `InternetService`

---

## 🧹 Data Cleaning Steps

- Removed duplicates and invalid `customerID`s
- Converted data types (e.g. `TotalCharges` to float)
- Standardized categorical values (e.g. "No internet service" treated separately)
- Filtered and grouped fields for analysis

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

- **Churn Rate**: ~27% of customers have churned
- **High churn among**: 
  - Senior citizens
  - Month-to-month contract holders
  - Customers using electronic check
- **Lower churn**:
  - Annual or 2-year contracts
  - Auto-payment methods like bank transfers or credit cards
- **Streaming services** have a mild correlation with churn
- Customers without phone/internet service churn less

---

## 🧰 Tools & Tech Used

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard building & visualization |
| **Python (Pandas)** | Data cleaning & initial analysis |
| **GitHub** | Portfolio project hosting |
| **Excel** | Quick previews |

---

## 📌 Conclusion

This project demonstrates how business intelligence tools like Power BI can uncover actionable insights from telecom churn data. It emphasizes the importance of customer demographics, payment methods, and service types in predicting churn.

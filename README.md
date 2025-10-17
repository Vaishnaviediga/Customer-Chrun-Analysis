# Customer-Chrun-Analysis

# Customer Churn Retention Dashboard

## Table of Contents
- [Problem Statement]
- [Datasource]
- [Data Preparation]
- [Data Modeling] 
- [Data Analysis (DAX)]  
- [Data Visualization (Dashboard)]
- [Insights]
- [Recommendations]



## Problem Statement
The goal of this project is to analyze customer churn and create a retention dashboard that provides insights to the management. The dashboard focuses on identifying customers who are likely to churn, understanding the demographics of these customers, and tracking key KPIs to help in retention strategies.  

The analysis also focuses on demographic information about customers – **gender, whether they have partners or dependents.  

---

## Datasource
The dataset used for this project was obtained from Kaggle.  
It includes customer data for a telecom company with multiple attributes like tenure, services subscribed, charges, and demographic information.  

---

## Data Preparation
- Removed unnecessary columns that did not add value to the analysis.  
- Removed unnecessary rows (duplicates or irrelevant entries).  
- Validated each column to ensure the correct data type.  
- Cleaned categorical values for better consistency (e.g., `SeniorCitizen` converted to `Yes/No`).  

---

## Data Modeling
- After cleaning, the dataset was transformed and structured to be ready for data modeling.  
- Relationships were maintained and tables were organized for efficient use in Power BI.  

---

## Data Analysis (DAX)
- Measures were created in Power BI using **DAX** to calculate KPIs such as:  
  - Average Monthly Charges  
  - Average Total Charges  
  - Churn Rate  
- Additional calculated measures were created to analyze customer behavior and subscription patterns.  

---

## Data Visualization (Dashboard)
- An interactive Power BI dashboard was created using the cleaned dataset and DAX measures.  
- The dashboard includes:  
  - KPI cards for key metrics  
  - Charts and graphs to visualize churn patterns  
  - Slicers for filtering by demographics and services  
- Users can interact with the dashboard to explore churn trends and insights.  

---

## Insights
- Customers without partners or dependents were observed to have a higher churn rate.  
- Certain service subscriptions (like online backup or tech support) correlate with lower churn probability.  
- Senior citizens showed different churn behavior compared to other age groups.  

---

## Recommendations
- Focus retention campaigns on customers without partners or dependents.  
- Encourage subscription to value-added services like online backup and tech support to reduce churn.  
- Monitor senior citizen customer behavior and create tailored retention strategies for them.  

---

## Files in this Repository
| File | Description |
|------|-------------|
| `Churn_Dataset.xlsx` | Raw dataset used for analysis |
| `PowerBI_Dashboard.pbix` | Power BI file containing the dashboard |
| `README.md` | Project documentation |

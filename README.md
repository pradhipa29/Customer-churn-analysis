# Customer Churn Analysis (Python)

### Telecom Customer Retention Analysis | Python · Pandas · Matplotlib · Seaborn

## Overview

This project performs exploratory data analysis (EDA) on telecom customer data to understand churn behavior and identify key factors affecting customer retention.

The dataset contains 7,032 customers, and the goal is to:
- Analyze churn patterns  
- Identify high-risk customers  
- Understand revenue impact  
- Generate business insights

## Business Objective

**Identify why customers are leaving and how to reduce churn using data-driven insights.**

## Analysis Performed

- Data Cleaning and preprocessing  
- Handling missing values  
- Exploratory Data Analysis (EDA)  
- Feature analysis (contract, tenure, charges, payment method)  
- Correlation analysis  

## Key Insights

- Churn Rate: **26.6%** (1 in 4 customers)
- Month-to-Month: **Highest churn (42.7%)**
- Two-Year Contracts: **Lowest churn (2.8%)**
- Avg Monthly Charges (Churned): **$74.44**
- Avg Monthly Charges (Retained): **$61.31**
- High charges → higher churn  
- New customers → higher churn  
- Electronic check → highest churn  

## Visualizations

- Churn distribution (Pie chart)  
- Churn by contract type (Bar chart)  
- Monthly charges vs churn (Box plot)  
- Tenure distribution (Histogram)  
- Correlation heatmap  

## Business Recommendations

- Convert month-to-month customers to long-term plans  
- Focus on early-stage customers (0–12 months)  
- Encourage auto-pay over electronic check  
- Provide offers for high-paying customers  

## Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

## Dataset

- IBM Telco Customer Churn Dataset  
- 7,032 Customers · 21 Features  

## How to Run

```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook churn_analysis.ipynb

Author

Pradhipa S
Aspiring Data Analyst
📧 pradhipasuresh16@gmail.com
🔗 https://www.linkedin.com/in/pradhipa29

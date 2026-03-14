# Customer Churn Analysis Dashboard

## Project Overview
Customer churn is a major challenge for subscription-based businesses.  
This project analyzes customer behavior to identify patterns that lead to churn and visualizes the insights through an interactive dashboard.

The analysis pipeline was built using Databricks for data processing and Power BI for data visualization.

---

## Project Architecture

Kaggle Dataset  
↓  
Databricks (Data Processing using Python & SQL)  
↓  
Cleaned Data Table  
↓  
Power BI Dashboard  

---

## Tools & Technologies

- Databricks
- Python
- SQL
- Power BI
- GitHub

---

## Dataset
The dataset contains customer information including:

- Gender
- Contract Type
- Payment Method
- Monthly Charges
- Tenure
- Churn Status

Tenure represents the number of months a customer has been with the company.

---

## Dashboard Features

The Power BI dashboard includes:

- Total Customers KPI
- Churn Rate KPI
- Customer Churn Distribution
- Churn by Contract Type
- Churn by Payment Method
- Monthly Charges vs Churn
- Customer Tenure Distribution
- Interactive Filters (Gender, Contract, Payment Method)

---

## Dashboard Preview

![Dashboard](images/dashboard_preview.png)

---

## Key Insights

- Customers with **month-to-month contracts show the highest churn rate**.
- Customers with **tenure under 12 months are more likely to churn**.
- **Electronic check payment method** is associated with higher churn.
- Customers with **higher monthly charges show slightly increased churn probability**.

---

## How to Run the Project

1. Download the `.pbix` file from the repository.
2. Open it using Power BI Desktop.
3. Explore the dashboard and use filters to analyze churn behavior.

---

## Business Impact

Understanding churn patterns helps companies:

- Identify high-risk customers
- Improve retention strategies
- Reduce revenue loss

---

## Author

Rana Debnath  
Data Analyst | SQL | Python | Power BI | Databricks

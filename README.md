
# Customer Shopping Behavior Analytics

An end-to-end Data Analytics project that analyzes customer shopping behavior using **Python, SQL Server, and Power BI**. This project demonstrates the complete analytics workflow—from data cleaning and preprocessing to SQL-based business analysis and interactive dashboard development—to uncover actionable insights from retail transaction data.

---

## Project Overview

Retail businesses generate large volumes of customer transaction data every day. Analyzing this data helps organizations understand customer purchasing behavior, identify high-value segments, improve marketing strategies, and make data-driven business decisions.

In this project, customer shopping data was cleaned and transformed using Python, analyzed using SQL Server, and visualized through an interactive Power BI dashboard.

---

## Business Problem

The objective of this project is to answer key business questions such as:

- Which product categories generate the highest revenue?
- How do customer demographics influence purchasing behavior?
- Does subscription status affect customer spending?
- Which shipping methods are associated with higher purchase amounts?
- Which age groups contribute the most revenue?
- How can businesses improve customer retention and sales?

---

## Tech Stack

- **Python**
  - Pandas
  - NumPy
  - Jupyter Notebook
- **SQL Server**
- **SQL Server Management Studio (SSMS)**
- **Power BI**

---

## Dataset Information

- **Domain:** Retail / E-commerce
- **Total Records:** 3,900
- **Total Features:** 18

### Dataset includes:

- Customer Demographics
- Product Category
- Purchase Amount
- Subscription Status
- Shipping Type
- Previous Purchases
- Review Rating
- Discount Applied
- Purchase Frequency
- Season
- Product Details

---

## Project Workflow

### 1. Data Cleaning & Preprocessing (Python)

- Imported the dataset using Pandas.
- Performed Exploratory Data Analysis (EDA).
- Identified missing values.
- Imputed missing values in the **Review Rating** column.
- Standardized column names.
- Removed redundant columns.
- Created additional features:
  - Age Group
  - Purchase Frequency
- Prepared the cleaned dataset for SQL analysis.

---

### 2. SQL Business Analysis (SQL Server)

Imported the cleaned dataset into **SQL Server** and performed business analysis using SQL queries.

### Business Questions Solved

- Revenue by Gender
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription vs Non-Subscription Analysis
- Shipping Type Comparison
- Top Rated Products
- High Spending Discount Customers
- Discount-Dependent Products
- Customer Segmentation
- Top Products by Category
- Repeat Buyer Analysis

---

### 3. Interactive Dashboard (Power BI)

Developed an interactive dashboard to visualize business insights.

### KPI Cards

- Total Customers
- Average Purchase Amount
- Average Review Rating

### Visualizations

- Subscription Status Distribution
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group

### Interactive Filters

- Subscription Status
- Gender
- Category
- Shipping Type

---

## Dashboard Preview

<p align="center">
  <img src="Power BI/Dashboard.png" alt="Customer Behavior Dashboard" width="100%">
</p>

---

## Key Insights

- Clothing generated the highest revenue and sales.
- Young Adult customers contributed the highest overall revenue.
- Female customers generated slightly higher revenue than male customers.
- Non-subscribers represented the majority of customers.
- Express shipping customers showed a higher average purchase amount.
- Customer segmentation identified Loyal, Returning, and New customer groups based on purchase history.

---

## Business Recommendations

- Increase subscription adoption through exclusive customer benefits.
- Introduce loyalty programs to improve customer retention.
- Focus marketing campaigns on high-value customer segments.
- Promote high-performing product categories.
- Optimize shipping strategies to enhance customer satisfaction.
- Use customer insights to support data-driven business decisions.

---

## Repository Structure

```
Customer-Shopping-Behavior-Analytics
│
├── Dataset
│   └── shopping_trends.csv
│
├── Python
│   └── Customer_Shopping_Analysis.ipynb
│
├── SQL
│   └── Business_Queries.sql
│
├── Power BI
│   ├── Customer_Behavior_Dashboard.pbix
│   └── Dashboard.png
│
├── Documentation
│   ├── Business_Problem.pdf
│   └── Project_Presentation.pdf
│
├── README.md
└── LICENSE
```

---

## Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL Query Writing
- SQL Server
- Data Visualization
- Dashboard Development
- Business Intelligence
- Customer Analytics
- Retail Analytics
- Data Storytelling

---

## Future Improvements

- Build predictive models for customer purchasing behavior.
- Develop customer lifetime value (CLV) analysis.
- Create interactive forecasting dashboards.
- Deploy the dashboard using Power BI Service.
- Integrate real-time retail data sources.

---

## Author

**Nasrin567**

If you found this project useful, consider giving it a ⭐ on GitHub.

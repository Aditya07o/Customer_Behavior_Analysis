# 🛍️ Customer Shopping Behavior Analysis

<div align="center">

# 📊 End-to-End Data Analytics Project

### Transforming Raw Customer Data into Actionable Business Insights using **Python, PostgreSQL, SQL & Power BI**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Database-CC2927?style=for-the-badge&logo=mysql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Analyze • Clean • Query • Visualize • Report**

⭐ *A complete Data Analytics workflow demonstrating data preprocessing, SQL analysis, dashboard development, and business storytelling.*

</div>

---

# 📑 Table of Contents

- [📌 Overview](#-overview)
- [🎯 Business Problem](#-business-problem)
- [📂 Dataset Information](#-dataset-information)
- [🛠️ Tech Stack](#️-tech-stack)
- [🏗️ Project Architecture](#️-project-architecture)
- [📊 Exploratory Data Analysis](#-exploratory-data-analysis)
- [🧹 Data Cleaning](#-data-cleaning)
- [🗄️ SQL Business Analysis](#️-sql-business-analysis)
- [📈 Power BI Dashboard](#-power-bi-dashboard)
- [💡 Key Business Insights](#-key-business-insights)
- [📄 Report & Presentation](#-report--presentation)
- [📁 Project Structure](#-project-structure)
- [💼 Skills Demonstrated](#-skills-demonstrated)
- [🔮 Future Improvements](#-future-improvements)
- [👨‍💻 Author](#-author)

---

# 📌 Overview

Understanding customer purchasing behavior is one of the most valuable aspects of retail analytics. Businesses that analyze customer preferences can improve marketing campaigns, increase sales, enhance customer experience, and make data-driven decisions.

This project presents a complete **End-to-End Data Analytics Pipeline** that transforms raw shopping data into meaningful business insights.

The workflow covers:

- 📥 Data Loading
- 📊 Exploratory Data Analysis (EDA)
- 🧹 Data Cleaning & Transformation
- 🗄️ SQL Business Analysis
- 📈 Interactive Power BI Dashboard
- 📄 Business Report

---

# 🎯 Business Problem

A retail company wants to understand customer shopping behavior to improve sales performance, customer satisfaction, and long-term loyalty.

The objective is to identify patterns related to:

- Customer demographics
- Shopping preferences
- Product categories
- Discounts
- Reviews
- Seasons
- Subscription behavior
- Purchase frequency

These insights help management make informed decisions regarding marketing strategies, customer retention, and product planning.

---

# 📂 Dataset Information

| Feature | Details |
|----------|---------|
| Dataset | Customer Shopping Behavior |
| Records | **3,900** |
| Features | **18 Columns** |
| Data Type | Structured CSV |
| Domain | Retail Analytics |

### Dataset Includes

- 👤 Customer Demographics
- 🛍 Purchased Products
- 💰 Purchase Amount
- 🎯 Discounts
- ⭐ Product Ratings
- 📍 Locations
- 🚚 Shipping Type
- 💳 Payment Methods
- 🔁 Purchase Frequency
- 💎 Subscription Status

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Data Analysis |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Visualization |
| Seaborn | Statistical Charts |
| PostgreSQL | Database |
| SQL | Business Queries |
| Power BI | Dashboard |
| Gamma | Presentation |
| GitHub | Version Control |

---

# 🏗️ Project Architecture

```text
                    Customer Shopping Dataset
                              │
                              ▼
                  Python (EDA & Data Cleaning)
                              │
                              ▼
                 PostgreSQL Database Storage
                              │
                              ▼
                 SQL Business Query Analysis
                              │
                              ▼
               Power BI Interactive Dashboard
                              │
                              ▼
          Business Report + Gamma Presentation
```

---

# 📊 Exploratory Data Analysis

The dataset was explored using Python to understand its structure and identify trends.

### Tasks Performed

- Imported dataset using Pandas
- Checked data types
- Generated summary statistics
- Identified missing values
- Visualized distributions
- Detected outliers
- Studied customer purchasing patterns
- Examined product popularity

### Libraries Used

```python
Pandas
```

---

# 🧹 Data Cleaning

To ensure data quality, several preprocessing techniques were applied.

### Cleaning Steps

✔ Removed duplicate records

✔ Handled missing values

✔ Renamed columns

✔ Standardized data

✔ Feature Engineering

✔ Created Age Groups

✔ Improved readability

✔ Converted data types

✔ Prepared dataset for SQL analysis

---

# 🗄️ SQL Business Analysis

After cleaning, the dataset was imported into PostgreSQL for business analysis.

## Business Questions Solved

✅ Revenue by Gender

✅ High Spending Discount Customers

✅ Top Rated Products

✅ Shipping Type Comparison

✅ Subscribers vs Non-Subscribers

✅ Discount Dependent Products

✅ Customer Segmentation

✅ Top Products by Category

✅ Repeat Customer Analysis

✅ Revenue by Age Group

### SQL Concepts Used

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- CASE
- HAVING
- Aggregate Functions
- CTEs
- Window Functions

---

# 📈 Power BI Dashboard

An interactive dashboard was created to present business insights visually.

## Dashboard Features

📊 KPI Cards

📈 Sales Trends

📉 Customer Segmentation

🛍 Product Category Analysis

👥 Gender Analysis

🚚 Shipping Analysis

💳 Payment Method Distribution

⭐ Product Ratings

🎯 Interactive Filters

📌 Drill-down Visualizations

---

# 💡 Key Business Insights

📌 High-spending customers contribute significantly to total revenue.

📌 Customer subscriptions positively influence repeat purchases.

📌 Certain product categories consistently receive higher ratings.

📌 Discount strategies increase purchase frequency.

📌 Age groups exhibit different purchasing behaviors.

📌 Shipping preferences influence overall spending.

📌 Loyal customers generate greater lifetime value.

---

# 📄 Report & Presentation

The project includes professional documentation to communicate findings effectively.

### Included Deliverables

📄 Business Report

📊 Power BI Dashboard

🗄 SQL Queries

🐍 Python Notebook

---

# 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis
│
├── 📂 Dataset
│   └── customer_shopping_behavior.csv
│
├── 📂 Python
│   └── Customer_Shopping_Behavior_Analysis.ipynb
│
├── 📂 SQL
│   └── customer_behavior_sql_queries.sql
│
├── 📂 Dashboard
│   └── customer_behavior_dashboard.pbix
│
├── 📂 Report
│   └── Customer Shopping Behavior Analysis.pdf
│
├── 📂 Business Problem
│   └── Business Problem Document.pdf
│
├── 📂 Presentation
│   └── Gamma Presentation.pdf
│
└── 📄 README.md
```

---

# 📌 Project Statistics

| Metric | Value |
|---------|------:|
| Records | 3,900 |
| Features | 18 |
| Missing Values Handled | ✔ |
| SQL Queries | 10 |
| Dashboard | 1 |
| Report | 1 |
| Presentation | 1 |

---

# 💼 Skills Demonstrated

### Programming

- Python
- SQL

### Data Analysis

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Statistical Analysis

### Database

- PostgreSQL
- SQL Query Optimization

### Business Intelligence

- Power BI
- Dashboard Design
- KPI Development
- Data Storytelling

### Professional Skills

- Problem Solving
- Business Analysis
- Reporting
- Presentation
- Data Visualization

---

# 🔮 Future Improvements

- Integrate live PostgreSQL connection with Power BI

- Build predictive machine learning models

- Deploy dashboard on Power BI Service

- Automate ETL pipeline

- Add customer churn prediction

- Perform sentiment analysis on customer reviews

---

# 🌟 Why This Project?

This project demonstrates the complete lifecycle of a real-world Data Analytics solution—from raw data processing to business intelligence dashboards and executive reporting.

It showcases technical proficiency in **Python**, **SQL**, **PostgreSQL**, and **Power BI**, while emphasizing data-driven decision-making and effective communication of insights.

---

# 👨‍💻 Author

## **Aditya Telavane**

**Aspiring Data Analyst | Python | SQL | PostgreSQL | Power BI | Excel**

📧 Email: adityatelavane01@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/aditya-telavane-9862322a5/

---

<div align="center">
**Thank you for visiting!**

</div>

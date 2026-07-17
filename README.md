# 🛍️ Customer Shopping Behavior Analysis using SQL, Python & Power BI

An end-to-end Data Analytics project that analyzes customer shopping behavior using Python, SQL, and Power BI to generate business insights and interactive visualizations.

---

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional retail data containing **3,900 customer purchase records**. The objective is to transform raw customer data into meaningful business insights through data preparation, SQL analysis, and interactive dashboards.

The project follows a complete analytics workflow starting from data cleaning and ending with business recommendations.

---

## 📊 Dashboard Preview

![Customer Shopping Behavior Dashboard](powerbi/dashboard.png)

---


## 🎯 Business Problem

A leading retail company wants to better understand customer shopping behavior to improve sales, customer satisfaction, and long-term customer loyalty.

The objective is to identify trends across:

- Customer demographics
- Product categories
- Purchase behavior
- Discounts
- Subscription status
- Shipping preferences
- Customer reviews

The insights generated help support better marketing strategies and business decisions.

---

## 📂 Dataset Summary

**Dataset Size**

- Total Records: **3,900**
- Total Columns: **18**

### Dataset Features

- Customer Demographics
- Purchase Details
- Shopping Behavior
- Subscription Status
- Payment Method
- Shipping Type
- Previous Purchases
- Review Rating
- Discount Information

---

## 🛠️ Technologies Used

- Python
- Pandas
- SQL (PostgreSQL)
- Power BI
- Jupyter Notebook
- Microsoft Excel

---

## 📊 Dashboard Highlights

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue by Product Category
- Sales by Product Category
- Revenue by Age Group
- Sales by Age Group
- Customer Subscription Distribution
- Interactive Filters
  - Subscription Status
  - Gender
  - Product Category
  - Shipping Type

---

## 🔄 Project Workflow

```
Raw Dataset
      │
      ▼
Python Data Cleaning & Preparation
      │
      ▼
Exploratory Data Analysis
      │
      ▼
PostgreSQL Database
      │
      ▼
SQL Business Analysis
      │
      ▼
Power BI Dashboard
      │
      ▼
Business Insights & Recommendations
```

---

## 🐍 Data Preparation using Python

The dataset was prepared using Python by performing:

- Data Import
- Data Exploration
- Missing Value Handling
- Column Standardization
- Feature Engineering
- Data Consistency Checks
- Loading Cleaned Data into PostgreSQL

---

## 🗄️ Business Analysis using SQL

SQL was used to answer business questions including:

1. Revenue by Gender
2. High-Spending Discount Users
3. Top 5 Products by Rating
4. Shipping Type Comparison
5. Subscribers vs Non-Subscribers
6. Discount-Dependent Products
7. Customer Segmentation
8. Top 3 Products per Category
9. Repeat Buyers & Subscription Analysis
10. Revenue by Age Group

---

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive overview of customer shopping behavior through KPI cards, category-wise analysis, age group analysis, and interactive slicers.

- Revenue Analysis
- Customer Segmentation
- Subscription Analysis
- Shipping Analysis
- Product Performance
- Age Group Revenue Analysis

---

## 💡 Business Recommendations

Based on the analysis:

- Promote exclusive benefits for subscribers.
- Reward repeat customers through loyalty programs.
- Review discount strategies to balance profitability.
- Highlight top-rated products in marketing campaigns.
- Target high-revenue customer segments with personalized campaigns.

---

## 📁 Repository Structure

```text
customer-shopping-behavior-analysis
│
├── README.md
│
├── data
│   └── customer_shopping_behavior.csv
│
├── docs
│   └── business_problem_document.pdf
│
├── notebooks
│   └── customer_shopping_behavior_analysis.ipynb
│
├── powerbi
│   ├── customer_behavior_dashboard.pbix
│   └── dashboard.png
│
└── sql
    └── customer_behavior_sql_queries.sql
```

---

## 🚀 How to Run

### Clone the repository

```bash
git clone https://github.com/PurnaMC/customer-shopping-behavior-analysis.git
```

### Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

- notebooks/customer_shopping_behavior_analysis.ipynb

Execute the notebook to clean and prepare the dataset.

### SQL Analysis

- Import the cleaned dataset into PostgreSQL.
- Execute the SQL queries available in:

```
sql/customer_behavior_sql_queries.sql
```

### Power BI Dashboard

Open:

```
powerbi/customer_behavior_dashboard.pbix
```

Refresh the data connection if required.

---

## 📚 Skills Demonstrated

- Data Cleaning
- Data Preparation
- Exploratory Data Analysis
- Feature Engineering
- SQL Query Writing
- PostgreSQL
- Data Visualization
- Power BI Dashboard Development
- Business Analysis

---

## 👨‍💻 Author

**Mallula Purna Chandra**

GitHub: https://github.com/PurnaMC

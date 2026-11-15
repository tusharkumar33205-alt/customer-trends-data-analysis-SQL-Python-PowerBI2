# 🛍️ Customer Shopping Behavior Analysis

### End-to-End Data Analytics Project Using Python, SQL & Power BI

![Python](https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-Database-orange?logo=postgresql)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview

Customer Shopping Behavior Analysis is a data analytics project focused on understanding customer purchasing patterns, product preferences, subscription behavior, and shopping trends.

The project uses Python for data cleaning and exploratory data analysis, SQL for querying and extracting business insights, and Power BI for interactive dashboard visualization.

The objective is to transform raw customer shopping data into meaningful insights that can support business decisions, improve customer engagement, and help understand purchasing behavior.

## 🎯 Project Objectives

- Analyze customer shopping behavior and purchasing patterns.
- Identify popular products and product categories.
- Understand customer demographics and preferences.
- Compare purchasing behavior between subscribers and non-subscribers.
- Analyze discount usage and shipping preferences.
- Identify customer segments based on previous purchases.
- Build an interactive Power BI dashboard.
- Generate actionable business recommendations.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data cleaning and exploratory data analysis |
| Pandas | Data manipulation and preprocessing |
| Jupyter Notebook | Python analysis environment |
| SQL | Database management and business analysis |
| Power BI | Interactive dashboard and visualization |
| CSV | Dataset storage |

## 📂 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Business Problem_Document.pdf
│
├── Customer Shopping Behavior Analysis.pdf
│
├── Customer_Shopping_Behavior_Analysis.ipynb
│
├── customer_behavior_dashboard.pbix
│
├── customer_behavior_sql_queries.sql
│
├── customer_shopping_behavior.csv
│
├── Customer-Shopping-Behavior-Analysis.pptx
│
├── LICENSE
│
└── README.md
```

*File and folder names may vary slightly depending on the repository version.*

## 📊 Dataset Description

The dataset contains **3,900 customer purchase records** and 18 original attributes.

Important attributes include:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount (USD)
- Location
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Previous Purchases
- Payment Method
- Frequency of Purchases

## 🐍 Python – Data Cleaning & Exploratory Data Analysis

Python and Pandas are used to:

1. Import and inspect the dataset.
2. Identify missing values.
3. Handle missing review ratings using category-wise median imputation.
4. Standardize column names.
5. Perform exploratory data analysis.
6. Create age groups.
7. Convert purchase frequency into approximate day intervals.
8. Prepare the dataset for SQL analysis.

## 🗄️ SQL – Business Analysis

SQL is used to answer important business questions.

The project includes 10 analytical queries:

1. Total purchase amount by gender.
2. Customers who used discounts and spent above average.
3. Top five products based on average review rating.
4. Comparison of average purchase amount by shipping type.
5. Comparison between subscribers and non-subscribers.
6. Products with the highest discount usage.
7. Customer segmentation based on previous purchases.
8. Top three most purchased products in each category.
9. Relationship between repeat purchases and subscription status.
10. Purchase amount analysis by age group.

SQL concepts used include:
- SELECT and WHERE
- GROUP BY
- Aggregate Functions
- Subqueries
- CASE Statements
- Common Table Expressions (CTEs)
- Window Functions
- ROW_NUMBER()

## 📈 Power BI – Interactive Dashboard

The Power BI dashboard provides a visual overview of customer shopping behavior.

### Dashboard Features

- Total Customer Count
- Average Purchase Amount
- Average Review Rating
- Subscription Status Analysis
- Revenue by Product Category
- Sales by Product Category
- Revenue by Age Group
- Sales by Age Group

### Interactive Filters

- Subscription Status
- Gender
- Category
- Shipping Type

The dashboard helps users explore customer segments and compare purchasing patterns interactively.

## 🔍 Key Business Findings

Based on the supplied dataset:

- Total recorded purchase amount: **$233,081**
- Total purchase records: **3,900**
- Average purchase amount: **$59.76**
- Average review rating after imputation: approximately **3.75/5**
- Clothing contributes the highest purchase amount among product categories.
- Male records contribute a higher aggregate purchase amount, partly because they are more numerous.
- Subscribers and non-subscribers have similar average purchase amounts.
- Express shipping records have a slightly higher average purchase amount than Standard shipping.

*These findings are descriptive and apply to the supplied dataset. They do not establish causal relationships.*

## 💡 Business Recommendations

- Focus marketing efforts on popular product categories.
- Use customer reviews to understand product satisfaction.
- Evaluate discount strategies using sales and profitability data.
- Investigate customer subscription patterns.
- Improve customer segmentation for targeted marketing.
- Monitor shipping preferences to improve customer experience.

## 🚀 How to Run This Project

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Install Python dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy jupyter
```

Install the appropriate database driver depending on your SQL database.

### 3. Run the Python Notebook

Open:

`Customer_Shopping_Behavior_Analysis.ipynb`

Run the notebook cells sequentially.

### 4. Execute SQL Queries

Open:

`customer_behavior_sql_queries.sql`

Connect to the configured database and execute the queries.

Note: The supplied SQL script uses PostgreSQL-compatible syntax. Adapt queries if using MySQL or SQL Server.

### 5. Open the Power BI Dashboard

Open:

`customer_behavior_dashboard.pbix`

using Microsoft Power BI Desktop.

Verify the dataset connection if Power BI requests a data-source update.

## 📚 Learning Outcomes

Through this project, the following skills are demonstrated:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- SQL Query Writing
- Database Integration
- Customer Segmentation
- Business Intelligence
- Data Visualization
- Analytical Thinking
- Business Insight Generation

## 👨‍💻 Project Information

**Student:** Tushar Kumar

**Roll Number:** 17042402842

**Department:** Electronics Technology

**Programme:** B.Tech

**Project Domain:** Data Analytics



---

⭐ If you find this project useful, consider starring the repository.

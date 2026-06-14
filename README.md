# SQL Data Warehouse Analytics – Exploratory Data Analysis (EDA)

## 📊 Project Overview

This project is an **Exploratory Data Analysis (EDA)** performed on a SQL Server-based dimensional data warehouse.

The goal of this project is to analyze **sales, customers, and products data** in order to generate business insights, key performance indicators (KPIs), and performance trends.

The analysis follows a structured approach including database exploration, data profiling, aggregation analysis, and business reporting.

---

## 🎯 Objectives

- Explore database structure and metadata
- Analyze customer demographics and geography
- Evaluate product categories and performance
- Measure sales performance and revenue trends
- Build key business KPIs
- Identify top and bottom performing products and customers
- Document business rules and logic

---

## 🧱 Database Schema

The project is built on a **star schema data warehouse model**:

### Fact Table
- `gold.fact_sales` → Contains transactional sales data

### Dimension Tables
- `gold.dim_customers` → Customer details (name, gender, country, birthdate)
- `gold.dim_products` → Product details (category, subcategory, cost, name)

---

## 📈 Key Business KPIs

- Total Sales (Revenue)
- Total Quantity Sold
- Average Price
- Total Orders
- Total Products
- Total Customers
- Sales Date Range

---

## 🔍 Analysis Performed

### 👥 Customer Analysis
- Customers by country
- Customers by gender
- Age distribution (oldest & youngest customers)
- Top customers by revenue

### 📦 Product Analysis
- Product distribution by category
- Average cost per category
- Top 5 best-selling products
- Bottom 5 worst-selling products

### 💰 Sales Analysis
- Total revenue by category
- Revenue by customer
- Quantity sold by country
- Sales performance over time

---

## 🛠️ Tools & Technologies

- SQL Server
- T-SQL (Transact-SQL)
- Data Warehousing Concepts
- Analytical SQL (GROUP BY, JOINs, Window Functions)

---

## 📁 Project Structure
sql-data-warehouse-eda/
│
├── sql/
│ └── eda_queries.sql
│
├── docs/
│ ├── business_rules.md
│ └── query_explanation.md
│
├── screenshots/
│ └── (query results images)
│
└── README.md


---

## 📊 Example Insights

- Identified top 5 products generating highest revenue
- Determined customer segments by country and gender
- Found sales distribution across geographic regions
- Measured performance differences between product categories

---

## 🎓 Learning Source

This project was built as part of a hands-on SQL Data Warehouse course by:

**Baraa Khatib Salkini (Data With Baraa)**  
🔗 https://www.linkedin.com/in/baraa-khatib-salkini/  

📺 Course:
https://www.youtube.com/watch?v=SSKVgrwhzus&list=PLNcg_FV9n7qZY_2eAtUzEUulNjTJREhQe

---

## 🚀 Author

**Ahmed El Gammaz**

🔗 GitHub:  
https://github.com/Ahmed-ElGammaz/sql-data-warehouse-analytics-eda  

---

## 📌 Notes

- This project is intended for learning and portfolio purposes.
- Data is assumed to be from a structured data warehouse environment.
- Business logic and KPIs are based on standard data analytics practices.

---

## ⭐ If you like this project

Feel free to ⭐ the repository and connect on LinkedIn!

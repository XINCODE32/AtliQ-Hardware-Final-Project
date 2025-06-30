# 🧠 AtliQ Hardware Sales Audit & Product Analysis (PWC Project)

## 📌 Project Overview

AtliQ Hardware, a leading computer hardware manufacturer in India and abroad, partnered with PWC to conduct a detailed audit of their sales data and automate reporting. As part of this effort, our team was asked to perform a comprehensive **Financial Analysis** using a structured SQLite database provided by the client.

The goal is to identify revenue/ profit/ margin momentum, understand sales dynamics across time and markets, and deliver actionable insights through interactive dashboards.

---

## 🗂️ Project Objectives

🧮 **Deliverables**
- Clean and well-documented SQL queries
- Exploratory data analysis (EDA)
- Trend and performance dashboards (Power BI / Tableau)
- Insightful visualizations and business commentary

---

## 📁 Data Description

Data is provided in **SQLite format**. No CSV export is allowed; all work must be performed using SQL queries.

### 🧩 Expected Tables
| Table Name       | Description                                      |
|------------------|--------------------------------------------------|
| `fact_sales`     | Sales transactions with quantity & date info     |
| `dim_products`   | Product details like category, segment, variant  |
| `dim_customers`  | Customer data, including market and region       |
| `dim_date`       | Calendar information (year, quarter, month)      |
| `dim_markets`    | Market and region mapping                        |
| `product_prices` | Pricing info: gross price, discounts, etc.       |

---

## 🧪 Methodology

### 1. **Data Exploration & ERD Mapping**
- Inspect table relationships (foreign keys, joins)
- Build an Entity Relationship Diagram (ERD)

### 2. **Key Metrics Calculated**
- Total & average revenue per product
- Units sold by product/category/segment
- Time-based product sales trends
- Product popularity by market/region
- Profitability by product line (if cost data available)

### 3. **Tools & Tech Stack**
- SQLite (DB Browser or SQLAlchemy)
- Jupyter Notebook (Python + SQL)
- Power BI / Tableau for dashboards

---

## 📊 Sample Visualizations

- 📈 Product Revenue Over Time (Line chart)
- 🧺 Top 10 Products by Quantity Sold (Bar chart)
- 🌍 Product Sales by Region (Map/Heatmap)
- 🔄 Monthly Sales Trends (Area chart)
- 🧱 Category-wise Contribution to Total Revenue (Treemap)

---

## ✅ Project Outcomes

- Identified top-performing product categories and variants
- Tracked sales cycles and regional preferences
- Delivered an automated dashboard for internal teams
- Provided product-level recommendations for inventory & marketing

---

## 🧹 Data Cleaning Notes

See the `Data_Cleaning_Log.md` file for details on:
- Null handling
- Inconsistent category/segment naming
- Duplicate entries
- Data type formatting

---


## 🧾 License

This project is for educational/auditing purposes under NDA with AtliQ Hardware and PWC. No public data sharing permitted.

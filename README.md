# Task 6: Sales Trend Analysis Using Aggregations

## 📁 Dataset
The dataset used is the `superstore.xlsx` file, which contains detailed sales records including order dates, sales amounts, product categories, and regions. Data was cleaned and formatted to ensure compatibility with SQL analysis.

## 🎯 Objective
The objective of this task is to analyze sales trends in the Superstore dataset using SQL. The analysis focuses on understanding how revenue and order volumes fluctuate over time. It includes:
- Calculating monthly and annual revenue.
- Analyzing average sales per order.
- Identifying top-performing months and years.
- Evaluating order volume distribution across product categories.
- Applying SQL aggregation and date functions to generate insights that support business decisions.

## 🛠️ Tools & Techniques
- **SQL** (MySQL / PostgreSQL / SQLite)
- `SUM()`, `AVG()`, `COUNT(DISTINCT)`
- `STR_TO_DATE()`, `YEAR()`, `MONTH()`
- `GROUP BY`, `ORDER BY`, `LIMIT`

## 📊 Analysis Performed
- Monthly revenue and order volume trends.
- Top 3 highest revenue-generating months.
- Year-wise total revenue.
- Average monthly sales per order.
- Monthly order volume by product category.
- Highest selling product by year (using `RANK()` window function in MySQL 8.0+).

## 📌 Key Insights
- 2016 was the highest revenue-generating year.
- Office Supplies had the highest order volume across months.
- September 2016, June 2015, and December 2017 were peak months in revenue.
- Sales and order volumes vary significantly by category and season.

## 📂 Files Included
- `superstore_cleaned.csv` – cleaned dataset with formatted `ORDER_DATE`
- `task6_queries.sql` – SQL queries used in the analysis
- `screenshots/` – screenshots of query results
- `README.md` – this documentation

## ✅ How to Run
1. Load the `superstore_cleaned.csv` into your SQL database.
2. Use the SQL queries provided in `task6_queries.sql`.
3. Execute the queries in the order listed or modify them for deeper exploration.

## 📝 Conclusion
This task provided a hands-on understanding of how to apply SQL aggregation techniques to analyze sales data over time. The insights gained can help businesses make informed decisions regarding inventory, marketing, and operational planning.


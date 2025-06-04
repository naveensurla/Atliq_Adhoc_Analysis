# Atliq_Adhoc_Analysis
This project analyzes sales and product data from the gdb023 database using SQL and Python. It uncovers insights on customer markets, product growth, sales trends, discounts, and channel contributions, combining precise queries with visualizations from python to support data-driven business decisions in sales and marketing.


# 📊 SQL Data Analysis & Visualizations

This repository contains **10 SQL data analysis queries** and **corresponding Python visualizations** using the `gdb023` database, which includes sales, customer, product, discount, and profitability data.

---

## 📁 Repository Structure

📦SQL-Data-Analysis-Visualizations
┣ 📂sql
┃ ┣ 1_markets_by_customer.sql
┃ ┣ 2_product_increase_2021.sql
┃ ┣ 3_products_by_segment.sql
┃ ┣ 4_segment_product_increase.sql
┃ ┣ 5_products_high_low_cost.sql
┃ ┣ 6_top_customers_discount.sql
┃ ┣ 7_gross_sales_by_month.sql
┃ ┣ 8_total_sold_quantity_quarter.sql
┃ ┣ 9_gross_sales_by_channel.sql
┃ ┗ 10_top_products_per_division.sql
┣ 📂python_visualizations
┃ ┣ 3_products_by_segment.py
┃ ┣ 4_segment_product_increase.py
┃ ┣ 6_top_customers_discount.py
┃ ┣ 7_gross_sales_by_month.py
┃ ┣ 8_total_sold_quantity_quarter.py
┃ ┗ 9_gross_sales_by_channel.py
┣ README.md
┗ requirements.tx

## 🚀 Getting Started

### 1️⃣ Prerequisites

- **Python 3.8+**
- **MySQL Server**
- Python libraries:
  - pandas
  - mysql-connector-python
  - matplotlib
  - seaborn

Install dependencies:
```bash
pip install -r requirements.txt


2️⃣ Database Connection
Make sure the gdb023 database is accessible and credentials are set properly in each Python script:

host = "localhost"
user = "root"
password = "root"
database = "gdb023"



📌 SQL Queries
#	Query Description
1	Markets by Customer – List of markets where "Atliq Exclusive" operates in APAC.
2	Product Increase (2021 vs 2020) – Percentage increase in unique products.
3	Product Count by Segment – Unique product count by segment.
4	Segment-wise Increase (2021 vs 2020) – Increase in unique products by segment.
5	Highest & Lowest Manufacturing Cost – Products with highest and lowest costs.
6	Top 5 Customers by Discount (2021) – Customers with highest average discounts.
7	Gross Sales by Month (Atliq Exclusive) – Monthly gross sales trend.
8	Total Sold Quantity by Quarter (2020) – Highest sold quantity by quarter.
9	Gross Sales by Channel (2021) – Contribution of each channel.
10	Top Products per Division (2021) – Top 3 products per division by sold quantity.


📈 Visualizations
The following queries include Python visualizations:

3_products_by_segment.py

4_segment_product_increase.py

6_top_customers_discount.py

7_gross_sales_by_month.py

8_total_sold_quantity_quarter.py

9_gross_sales_by_channel.py

Each script:
✅ Connects to MySQL
✅ Executes the SQL query
✅ Loads data into pandas
✅ Generates a plot using matplotlib & seaborn
✅ Adds titles, labels, and annotations





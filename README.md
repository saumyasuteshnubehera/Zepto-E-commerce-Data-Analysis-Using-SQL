🛒 Zepto SQL Data Analysis Project

📌 Project Overview

• This project focuses on analyzing Zepto product dataset using SQL to derive valuable business insights.
• The dataset contains product details such as category, price, discounts, stock availability, weight, and more.
• SQL queries are written to explore, clean, and analyze data to answer key business questions.

📂 Dataset Details

• File Used: zepto_v2.csv
• Table Name: zepto
• Schema:
• sku_id – Unique product ID
• category – Product category
• name – Product name
• mrp – Maximum retail price
• discountPercent – Discount applied on MRP (%)
• availableQuantity – Quantity available in stock
• discountedSellingPrice – Selling price after discount
• weightInGms – Product weight in grams
• outOfStock – Availability status (True/False)
• quantity – Quantity sold

🛠️ Data Exploration

• Checked row count
• Sampled first 10 records
• Identified null values in columns
• Listed distinct product categories
• Compared in-stock vs. out-of-stock products
• Found duplicate product names

🧹 Data Cleaning

• Removed products with MRP = 0 or Selling Price = 0
• Converted paise to rupees for price columns
• Verified data consistency post-cleaning

📊 Data Analysis Questions & Insights

• Q1: Find the top 10 best-value products based on the highest discount percentage.
• Q2: Identify products with high MRP but currently out of stock.
• Q3: Calculate estimated revenue per category.
• Q4: Find products with MRP > ₹500 and discount < 10%.
• Q5: Identify the top 5 categories offering the highest average discount percentage.
• Q6: Calculate price per gram for products above 100g and sort by best value.
• Q7: Group products into categories based on weight: Low (<1kg), Medium (1–5kg), Bulk (>5kg).
• Q8: Calculate the total inventory weight per category.

📌 Tools & Technologies

• SQL (PostgreSQL / MySQL compatible)
• Dataset: zepto_v2.csv
• Queries: Zepto_SQL_Project.sql

🚀 How to Run the Project

• Create a new SQL database.
• Run the schema and queries from Zepto_SQL_Project.sql.
• Import the dataset (zepto_v2.csv) into the zepto table.
• Execute the SQL queries to explore and analyze.

📈 Business Use Case

• Understanding product pricing and discount strategy.
• Identifying revenue-driving categories.
• Analyzing stock availability trends.
• Optimizing inventory management.

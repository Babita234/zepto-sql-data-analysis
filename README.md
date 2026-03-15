Zepto Inventory Data Analysis (SQL Project)

This project performs end to end data analysis on Zepto e commerce inventory data using PostgreSQL. The objective is to explore product inventory information, clean the dataset, and extract meaningful business insights using SQL queries.

The project simulates a real world data analyst workflow, starting from raw data exploration to generating business focused insights from an e commerce inventory dataset.

This project highlights practical SQL skills required for Data Analyst roles including data exploration, data cleaning, transformation, and business analysis.

Tools Used

• PostgreSQL
• SQL
• Microsoft Excel

Dataset Description

The dataset contains product inventory information similar to what an e commerce platform maintains internally. Each record represents a product SKU listed in the catalog.

Duplicate product names may appear because the same product can exist in different package sizes, weights, discounts, or categories.

Dataset Columns

sku_id
Unique identifier for each product.

category
Product category such as fruits, snacks, beverages, dairy, and grocery items.

name
Product name listed in the catalog.

mrp
Maximum Retail Price of the product.

discountPercent
Discount percentage applied to the product.

discountedSellingPrice
Final selling price after discount.

availableQuantity
Total number of units currently available in inventory.

weightInGms
Weight of the product measured in grams.

outOfStock
Boolean value showing whether the product is available or out of stock.

quantity
Number of units included in the product package.

Project Workflow
1 Data Exploration

Initial exploratory analysis was performed to understand the dataset structure and product information.

Activities performed

• Counted the total number of records in the dataset
• Viewed sample rows to understand the data structure
• Checked for null values across columns
• Identified distinct product categories
• Compared in stock and out of stock products
• Detected duplicate product names representing multiple SKUs

2 Data Cleaning

Data cleaning was performed to improve data quality and consistency.

Steps performed

• Removed rows where product price values were zero
• Converted price values from paise to rupees for better readability
• Ensured consistent numeric formatting across price columns

3 Data Analysis

SQL queries were written to answer key business questions related to pricing, inventory, and product value.

Example analysis performed

Identified the top 10 products offering the highest discount

Found high price products that are currently out of stock

Estimated potential revenue for each product category

Filtered expensive products with minimal discount

Ranked categories offering the highest average discounts

Calculated price per gram to identify value for money products

Classified products into Low, Medium, and Bulk categories based on weight

Calculated total inventory weight by product category

Key Insights

• Highly discounted products can help attract more customers.
• Some expensive products were found to be out of stock, indicating potential lost sales.
• Certain categories contribute more to estimated revenue based on inventory levels.
• Price per gram analysis helps identify better value products for customers.

Skills Demonstrated

• SQL Query Writing
• Data Exploration
• Data Cleaning
• Business Data Analysis
• Inventory Data Analysis
• PostgreSQL Database Handling

Project Structure
zepto-sql-data-analysis

dataset
   zepto_inventory.xlsx

sql
   zepto_inventory_analysis.sql

images
   query_results.png

README.md

Author

Babita Kumari
Aspiring Data Analyst

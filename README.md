# Retail-Sales-Analysis---SQL-Project

# Objective

To clean, explore, and analyze transactional retail data using SQL by solving real-world business questions related to customer demographics, sales performance, and product trends.

# Tools & Technologies

- **Language**: SQL
- **Techniques**: Data Cleaning, Aggregation, CTEs, Window Functions, Date Functions, Case Statements

# Dataset Overview

The dataset contains transactional retail data stored in the `retail_sales` table with the following fields:

- `transaction_id` (Primary Key)
- `sale_date`, `sale_time`
- `customer_id`, `gender`, `age`
- `category` (Product category)
- `quantity`, `price_per_unit`, `cogs`, `total_sale`

# Key Analyses Performed

1. **Data Cleaning**
   - Removed rows with null values in key columns (e.g., `transaction_id`, `sale_date`, `category`).

2. **Customer Insights**
   - Counted total and unique customers.
   - Calculated average customer age by product category.

3. **Sales Analysis**
   - Calculated total and category-wise sales.
   - Identified high-value transactions and top 5 customers by revenue.

4. **Time-Based Analysis**
   - Determined best-selling months using `RANK()` and `EXTRACT()` functions.
   - Classified sales into **Morning**, **Afternoon**, and **Evening** shifts using `CASE` logic.

5. **Demographic Segmentation**
   - Segmented transactions by gender and category to understand purchasing patterns.

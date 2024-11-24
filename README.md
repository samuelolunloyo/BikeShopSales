# Bike Shop Sales Analysis Dashboard - Project Report

## Overview

This project involved designing an interactive dashboard for a bike shop's executive team to analyze sales data from 2016 to 2018. The project required querying the database using SQL to extract relevant data, building measures to calculate key metrics, and visualizing insights in Power BI. The purpose of this dashboard was to provide actionable insights into sales performance, product trends, and customer behavior.

---

## Task Breakdown

### 1. Data Extraction (SQL Query)
- Connected to the sales database to retrieve detailed sales data.
- Extracted fields such as:
  - **Customer information**: Name, city, state.
  - **Order details**: Date, quantity, revenue.
  - **Product attributes**: Name, category, brand.
  - **Store and sales representative details**.
- Grouped the data for aggregation, ensuring accurate calculations for each order.

### 2. Power BI Data Preparation
- Imported the extracted dataset into Power BI.
- Validated and inspected the data in Power Query for quality and consistency.
- Ensured the data was clean and ready for visualization.

### 3. Measures and Calculations
Built the following measures to provide granular insights:
- **Total Sales (Revenue)**: Sum of all sales revenue.
- **Order Count**: Number of orders placed.
- **Total Quantity**: Total units sold.
- **Average Order Value (AOV)**: Revenue per order.
- **Average Revenue per Order**: Average earnings from each transaction.
- **Average Units per Order (AUPO)**: Units sold per order.
- Created year-to-date (YTD) and previous-year-to-date (PYTD) comparisons for time-series analysis.

### 4. Interactive Visualizations
Designed multiple visualizations to present insights:
- **Sales Trends**: Line chart showing sales performance over time by quarter.
- **Revenue by City and Customer**: Bar charts highlighting the top-performing cities and customers.
- **Product and Category Analysis**:
  - Tree maps to showcase revenue contribution by products.
  - Bar charts to analyze sales by product categories (e.g., Mountain Bikes, Road Bikes).
- **Brand Sales Distribution**: Pie chart displaying brand-wise revenue share.
- **Time-Based Analysis**: Slicers for filtering data by year and state.

---

## Key Insights for the Bike Shop

### 1. Sales Performance
- Total sales for the analyzed period amounted to **$8.58M**, with a clear peak in 2017, followed by a decline in 2018.
- Quantity sold during this period reached **7K units**, with an **Average Order Value (AOV)** of **1.82K**.

### 2. Top Customers and Cities
- The top customers generated the highest revenue (e.g., **Pamelia Newman** and **Abby Gamble**).
- Cities like **Mount Vernon**, **Ballston Spa**, and **San Angelo** were top contributors to the revenue.

### 3. Product and Category Trends
- **Mountain Bikes** were the best-selling category, followed by **Road Bikes** and **Electric Bikes**.
- Products such as **Trek Slash 8 27.5 - 2016** and **Trek Conduit+ - 2016** were the top revenue generators.

### 4. Brand Performance
- **Trek** dominated with nearly **60% of the total sales**, followed by brands like **Surly** and **Electra**.

### 5. Decline in 2018
- Notable sales decline observed in 2018. This could prompt the executive team to investigate market dynamics, customer engagement strategies, or operational inefficiencies.

---

## How to Use the Dashboard

1. **Year and State Slicers**:
   - Filter data by year (2016, 2017, 2018) or by state to drill down into specific regions or time periods.

2. **Interactive Metrics**:
   - Use dynamic charts to identify top-performing products, categories, and customers.
   - Compare year-to-date sales performance against previous years.

3. **Actionable Insights**:
   - Identify which cities or customers to target for upselling or promotional campaigns.
   - Focus on expanding the best-performing product categories or brands.

---

## Conclusion

This project provided the bike shop with a comprehensive view of its sales data, helping the executive team make informed decisions on inventory, marketing, and operational strategies. The interactive dashboard ensures flexibility for analyzing past trends while setting a benchmark for future growth opportunities.

---

### Files and Visuals
- **SQL Query**: Extracted from the shop's database (included in the repository).
- **Power BI Dashboard**: Screenshots provided for visualization reference.

Feel free to explore the project for further improvements or additional analysis!

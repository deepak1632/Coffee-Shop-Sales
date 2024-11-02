# Coffee-Shop-Sales

## Project Overview

This Excel workbook provides an in-depth analysis of sales data for a coffee shop business, enabling stakeholders to gain insights into sales performance, identify trends, and make informed, data-driven decisions. Through a combination of descriptive and interactive visualizations, this workbook highlights key metrics like revenue growth, product popularity, and peak sales times. These insights support strategies for optimizing inventory, enhancing customer engagement, and improving overall profitability.

## Problem Statement

The workbook is designed to address key business questions about coffee shop sales. By analyzing sales metrics such as revenue, item popularity, and time-based trends, the report helps identify both high-performing products and opportunities for growth. The insights allow managers and analysts to adjust strategies based on customer preferences and seasonal demand, helping to optimize resources and boost profitability.

### Steps Followed

- **Step 1**: Loaded sales data from multiple sources into the workbook.
  
- **Step 2**: Cleaned and standardized currency formats, removed duplicates, and addressed missing values to ensure accuracy.
  
- **Step 3**: Verified data quality, assessed for missing values, and checked column formats.

- **Step 4**:Created new fields to categorize products based on revenue and popularity, and developed essential measures for analysis.
  
- **Step 5**: Added slicers for fields such as "Product Type," "Sales Date," and "Store Location" to allow for detailed exploration.

- **Step 6**: Generated key visualizations to showcase sales performance, revenue distribution, and product trends.

### Key Metrics

- **Total Revenue** : SUM(Sales_Data[Revenue])

- **Product Popularity %** : DIVIDE(SUM(Sales_Data[Quantity]), CALCULATE(SUM(Sales_Data[Quantity]), ALL(Sales_Data[Product_Type]))) * 100.

- **Average Order Value**: DIVIDE(SUM(Sales_Data[Revenue]), COUNT(Sales_Data[Order_ID])).


### Key Insights

1. **Top Performers:**
   -  Identified the highest revenue-generating products and popular items among customers.

2. **Revenue Trends:**
   - Monthly and seasonal revenue growth to pinpoint peak sales periods.

3. **Sales Volume analysis:**
   -  Trends in item quantity sold and demand patterns across locations.

### Visualizations and Analysis

1. **Bar Chart**: Shows revenue by product category over time.
  
2. **Line Chart**: Highlights monthly and seasonal sales trends, helping to spot peaks.

3. **Pie Chart**: Displays revenue share by product type, providing an overview of product contribution.

4. **Summary Cards**: Quick view of high-level metrics, like Total Revenue, Total Orders, and Average Order Value.

5. **Top Customers and Products**: Separate visuals for top-performing customers and products to aid in prioritization.


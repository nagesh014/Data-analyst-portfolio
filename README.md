Pizza Sales Analysis Project

A comprehensive data analysis and reporting project based on historical pizza store order data. This repository contains the data, cleaning scripts, exploratory data analysis, and dashboard visualizations used to extract key operational and sales insights.

Overview

The primary objective of this project is to analyze sales trends, peak operational hours, product performance, and customer ordering patterns to help optimize store inventory, staffing, and marketing strategies

Data Source & Model Structure

The dataset was sourced from Kaggle and consists of	pizza_id,order_id,pizza_name_id,quantity,order_date,order_day,order_time,unit_price,total_price,pizza_size,pizza_category,pizza_ingredients,pizza_name	String	

Key Performance Indicators (KPIs)

Based on the dataset calculations:

•	Total Revenue: $817,860.05
•	Total Pizzas Sold: 49,574
•	Total Orders: 21,350
•	Average Order Value (AOV): $38.31
•	Average Pizzas Per Order: 2.32

Insights & Analysis

1.	Daily & Hourly Trends: 
  o	Peak Days: Friday and Saturday experience the highest order volume and total sales.
  o	Peak Hours: Maximum orders occur during lunch (12:00 PM – 1:00 PM) and dinner (6:00 PM – 8:00 PM).
2.	Category Performance: 
  o	Classic Category leads overall sales volume and revenue, followed closely by Supreme and Chicken.
3.	Size Contribution: 
  o	Large and Medium sizes account for the vast majority of total sales revenue.
4.	Top & Bottom Performers: 
  o	Top Sellers: The Classic Deluxe Pizza, The Hawaiian Pizza, and The Pepperoni Pizza.
  o	Bottom Sellers: The Brie Carre Pizza (lowest overall sales and quantity).

Tools & Technologies
•	Microsoft Excel: Data storage, data cleaning, pivot tables, KPI summary sheets, and preliminary visualization charts.
•	Structured Query Language (SQL): Aggregations, metric verification, data transformation, and relational queries.

Project setup & usage
Excel File:
•	Open pizza_sales excel file(AutoRecovered).xlsx in Microsoft Excel.
•	View worksheet Sheet2 for summary metrics and Sheet3 for daily breakdown pivot tables.
SQL Execution:
•	Import the pizza_sales.db into standard SQL environments (e.g., MySQL, PostgreSQL, MS SQL Server).
•	Execute queries provided in the SQL Queries section to recreate the KPI metrics.

Dashboard Screenshot
<img width="1178" height="655" alt="Screenshot 2026-09-10 174350" src="https://github.com/user-attachments/assets/2e64e0a0-ab0e-4499-9962-a802a0c6d579" />


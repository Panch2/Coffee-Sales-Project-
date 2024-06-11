# Coffee-Sales-Project-

Coffee Shop Sales Analysis

Project Overview

This Excel project analyzes the sales data from a coffee shop to uncover trends and insights. The analysis includes calculating revenue, examining sales by month, day of the week, and hour of the day, and identifying top-selling products. The project concludes with a dynamic dashboard for easy visualization and interaction with the data.

Objectives

Prepare the data for analysis
Explore the data with PivotTables
Build a dynamic dashboard
Data Preparation

Steps:

Familiarize with the data:
Understand the dataset, including the number of transactions, the period covered, and the products sold.

Calculate Revenue:
Added a new column Revenue calculated as Price * Quantity.

Calculate Month and Day of Week:
Added columns for Month and Day of Week using formulas to convert transaction dates.
Month: =TEXT(TransactionDate, "mmm")
Day of Week: =TEXT(TransactionDate, "ddd")

Extract Hour:
Added a column Hour to extract the hour from the transaction time using the formula =HOUR(TransactionTime).
Data Exploration

PivotTables Created:

Revenue by Month:

Summarizes revenue for each month.
Inserted a PivotTable with Month in the Rows field and Revenue in the Values field.

Number of Transactions by Day of Week:

Shows the count of transactions for each day of the week.
Inserted a PivotTable with Day of Week in the Rows field and Transaction ID in the Values field (Count).
Number of Transactions by Hour of Day:

Displays the count of transactions for each hour of the day.
Inserted a PivotTable with Hour in the Rows field and Transaction ID in the Values field (Count).
Transactions by Product Category:

Counts transactions for each product category.
Inserted a PivotTable with Product Category in the Rows field and Transaction ID in the Values field (Count).
Transactions and Revenue by Product Type:

Shows the number of transactions and total revenue for each product type, sorted by the top 15 products.
Inserted a PivotTable with Product Type in the Rows field, Transaction ID (Count), and Revenue (Sum).
Dynamic Dashboard

Components:

Pivot Charts:

Revenue by Month: Line chart.
Transactions by Day of Week: Column chart.
Transactions by Hour of Day: Column chart.
Transactions by Product Category: Bar chart.
Slicer:

Added a slicer for Store Location to filter all PivotTables on the dashboard.
Layout:

Arranged the charts and slicer in a logical, user-friendly layout.
Hid raw PivotTables and removed gridlines for a cleaner presentation.
Insights and Recommendations

Key Insights:

Revenue Peaks: Revenue is highest in May and June.
Transaction Trends: Transactions are stable throughout the week, with a slight drop on Saturdays.
Peak Hours: Peak transaction hours are 8 AM to 10 AM.
Popular Products: Brewed chai tea and gourmet brewed coffee are top-selling products.

Recommendations:

Operational Adjustments: Increase staffing during peak hours.
Promotions: Target promotions on slower days, particularly Saturdays.
Product Focus: Promote top-selling products and explore new offerings in popular categories.
Usage Instructions

Open the Excel File:

Ensure macros are enabled if prompted.
Navigate the Dashboard:
Use the slicer to filter data by store location.
Review the charts for insights on sales trends.

Explore PivotTables:

PivotTables are hidden for a cleaner look but can be unhidden if needed for deeper analysis.
Conclusion

This project provides a comprehensive analysis of coffee shop sales data, offering valuable insights and recommendations for optimizing operations and marketing strategies. The dynamic dashboard facilitates easy interaction with the data, allowing for real-time exploration and decision-making.


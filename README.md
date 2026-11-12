# Sales Dashboard - Excel Project

## Overview
Sales analysis dashboard built in Excel to track total sales by region, category, and month.

## From CSV Files to Dashboard

1. Started with 3 CSV files: Orders.csv, Customers.csv, Products.csv
2. Imported CSV files into Excel with Power Query: Data > Get Data > From Text/CSV
3. Cleaned data in Power Query:
   - Removed duplicates and blank rows
   - Fixed data types: OrderDate to Date, Price to Number
   - Renamed columns
4. Transformed CSV data by Merging:
   - Merged Orders + Products on ProductID
   - Merged Orders + Customers on CustomerID
5. Created calculated column: Total Sales = Quantity * Price
6. Loaded clean data into Data Model
7. Built PivotTables from the clean data
8. Built final interactive Dashboard with Slicers

## Power Query
![Power Query](power-query.png)

## Pivot Table
![Pivot Table](pivot-table.png)

## Dashboard
![Dashboard](dashboard.png)

## Tools Used
Excel - Power Query - PivotTable - Slicers

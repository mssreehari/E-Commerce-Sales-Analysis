# Power BI E-Commerce Sales Analysis

## Overview
E-commerce sales data analysis using Power BI, Power Query, and data modeling.

## Dataset
- `List of Orders.csv`
- `Order Details.csv`
- `Sales target.csv`

## Tasks Completed
- Imported and transformed all datasets
- Kept first 500 orders
- Cleaned data types and customer names
- Created `Location`, `Profit Margin`, and `Profit Status`
- Checked missing and duplicate data
- Merged Orders and Order Details using `Order ID`
- Sorted orders by date and filtered by state
- Performed grouping and aggregation
- Created sales target summaries by month
- Established relationships between tables

## Data Model
- `Order Details` → `List of Orders` using `Order ID`
- `Order Details` → `Sales target` using `Category`

## Tools
- Power BI
- Power Query
- CSV

## Outcome
Prepared and modeled the e-commerce dataset for sales, profit, category, regional, and target analysis.

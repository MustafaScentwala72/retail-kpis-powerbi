# Retail KPIs “Zero-to-One” (Power BI)

## Goal
Build a decision-ready dashboard for Sales, Orders, Returns, and AOV.

## Dataset
Superstore (CSV)

## Tools
Power BI Desktop, Power Query, DAX, Git

## KPIs
- Total Sales
- Orders
- AOV
- Returned Orders
- % Returns
- Sales YoY
- Sales YoY %
- Sales Rolling 3M
- Sales Rolling 12M

## Pages
1. Executive: high-level KPIs and trend with Region slicer
2. Ops: sales breakdowns by Category, Region, Sub-Category
3. Product: top products and sales trend with Category and Sub-Category slicers
4. Customer: top customers with Segment and Region slicers

## Data model (star schema)
- FactSales
- DimDate
- DimCustomer
- DimProduct
- DimRegion
- Returns (linked by Order ID)

## Screenshots
See `exports/screenshots/`.

## How to use
1. Download the PBIX
2. Open in Power BI Desktop
3. Use slicers to filter and explore
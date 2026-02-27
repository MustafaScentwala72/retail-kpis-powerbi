# Retail KPIs “Zero-to-One” (Power BI)

A decision-ready Power BI dashboard built from the Superstore dataset to track Sales, Orders, AOV, and Returns with simple drill-down pages.

## Goal
Build a clean, decision-ready dashboard for:
- Total Sales
- Orders
- AOV (Average Order Value)
- % Returns
- Time trends (YoY and rolling trends)
- Breakdown by Category, Sub-Category, Region, Products, and Customers

## Dataset
- Superstore (CSV)

## Tools Used
- Power BI Desktop
- Power Query (data cleaning + shaping)
- DAX (measures)
- Git + GitHub

## What this dashboard helps answer
- Are sales going up or down over time?
- Which category and sub-category drives the most sales?
- Which region is performing best?
- Which products and customers contribute the most sales?
- What is the returns rate and how does it change with filters?

## Pages
- **Executive**: KPI cards + high-level trend and returns overview
- **Ops**: Sales breakdown by Category, Region, and Sub-Category
- **Product**: Top products by sales + sales trend with slicers
- **Customer**: Top customers by sales with Segment and Region slicing

## Key Measures (DAX)
- Total Sales
- Orders
- AOV
- Returned Orders
- % Returns
- Sales YoY
- Sales YoY %
- Sales Rolling 3M
- Sales Rolling 12M

## How to open
1. Download the `.pbix` file from this repo:
   - `Retail-KPIs-PowerBI.pbix`
2. Open it in **Power BI Desktop**
3. If prompted, allow the dataset refresh

## Repo structure
- `Retail-KPIs-PowerBI.pbix` → Power BI report file
- `exports/screenshots/` → dashboard screenshots for preview
- `README.md` → project documentation

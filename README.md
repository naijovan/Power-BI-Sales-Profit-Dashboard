# Sales & Profit Performance Dashboard

## Project Overview

This Power BI project analyses sales and profit performance across countries, products, customer segments, and time periods.

The goal of this project is to build an interactive dashboard that helps users understand overall business performance, identify top-performing products and segments, and analyse sales trends over time.

## Dashboard Preview

![Dashboard Overview](screenshots/dashboard_overview.jpg)

## Tools Used

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

## Dataset

This project uses Microsoft's Financial Sample dataset.

The dataset contains sales and profit data across different countries, products, customer segments, discount bands, and time periods.

## Dashboard Features

- KPI cards for Total Sales, Total Profit, Total Units Sold, and Profit Margin
- Sales trend analysis by month
- Sales breakdown by country
- Profit breakdown by product
- Sales breakdown by customer segment
- Interactive slicers for Year, Country, Segment, and Product

## DAX Measures Created

- Total Sales: `SUM(Financials[Sales])`
- Total Profit: `SUM(Financials[Profit])`
- Total Units Sold: `SUM(Financials[Units Sold])`
- Total Transactions: `COUNTROWS(Financials)`
- Average Sales: `AVERAGE(Financials[Sales])`
- Profit Margin: `DIVIDE([Total Profit], [Total Sales])`

## Key Insights

1. The dataset recorded total sales of 118.73M, total profit of 16.89M, and 1.13M units sold, with an overall profit margin of 14.23%.

2. The United States and Canada generated the highest sales among the countries analysed, while Mexico recorded the lowest sales.

3. Paseo generated the highest total profit among the products, making it the strongest contributor to profitability.

4. Government and Small Business were the strongest customer segments by sales.

5. Sales peaked around October, showing a strong increase in performance during the later part of the year.

## Skills Demonstrated

- Importing Excel data into Power BI
- Cleaning and preparing data using Power Query
- Creating DAX measures
- Building KPI cards and interactive visuals
- Using slicers for report filtering
- Designing a clean dashboard layout
- Generating business insights from data

## Files Included

- `Sales_Profit_Performance_Dashboard.pbix` - Power BI dashboard file
- `data/Financial Sample.xlsx` - Dataset used
- `screenshots/dashboard_overview.jpg` - Dashboard preview image
- `README.md` - Project documentation

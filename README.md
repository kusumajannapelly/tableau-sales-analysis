# Sales Analysis Dashboard (Tableau)

## Overview
An interactive Tableau dashboard that analyses retail sales performance 
across categories, regions, states, customer segments and time.

## Dataset
- **File:** Tableau_Sales_Analysis.xlsx (sheet: Sales Data)
- **Size:** 500 orders, 15 columns
- **Key fields:** Order Date, Segment, Region, State, City, Category, 
  Sub-Category, Product Name, Sales, Profit, Discount, Quantity

## What I Built
| Sheet | Visual |
|---|---|
| KPI Cards | Total Sales, Total Profit, Order Count, Average Discount |
| Monthly Sales Trend | Line chart of sales by month |
| Sales by Category | Bar chart |
| Profit by Sub-Category | Bar chart with colour for profit |
| Sales by Region | Sorted bar chart |
| Sales by State | Filled map of the US |
| Sales by Segment | Bar chart by customer segment |
| Monthly Profit Trend | Line chart of profit by month |
| Discount vs Profit | Scatter plot by product |
| Dashboard | Combined view with Region and Category filters |

## Interactivity
The Region and Category filters apply to every chart on the dashboard, 
including the KPI cards, the trend, the category chart and the map.

## Dashboard Preview
![Sales Dashboard](images/dashboard.png)

## Key Insights
- Total sales are 586,698, total profit is 40,902 across 500 orders, with 
  an average discount of 11.5%.
- Office Supplies leads in sales (294,089), followed by Furniture (152,381) 
  and Technology (140,228).
- South is the top region by sales (168,484), and Florida is the top state 
  (57,061).
- Consumer is the largest customer segment (311,510 in sales).
- Higher discounts go with lower profit: orders with no discount average 
  about 172 in profit, while orders with a 30% discount average a loss of 
  about 55.
- Monthly sales peak in July (76,550) and are lowest in May (30,690), with 
  the three years of data added together by month.

## Tools Used
Tableau, Excel# tableau-sales-analysis
Interactive Tableau sales dashboard with KPIs, trends, category, region and state analysis, and Region and Category filters.

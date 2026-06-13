# ☕ Coffee Sales Dashboard

## Project Overview

Interactive Excel dashboard analyzing coffee sales performance across countries, product types, and customer segments from **2019 to 2022**.

<br>

## Business Problem

A coffee retail business needed visibility into:

- Which coffee types drive the most revenue over time?
- Which countries contribute the most to total sales?
- Who are the highest-value customers?
- How do roast type, size, and loyalty card usage affect purchasing?

<br>

## Dataset Information

- **Source**: Kaggle - Coffee Sales Dataset
- **Period**: January 2019 – August 2022
- **Sheets**: Orders, Customers, Products
- **Key Fields**:
  - Order Date, Coffee Type, Roast Type, Size
  - Country, Customer Name
  - Sales (USD), Loyalty Card Status

<br>

## Analysis Process

### 1. Data Cleaning & Preparation

- Merged orders, customers, and products data using **XLOOKUP** and **INDEX-MATCH**
- Populated customer name, email, and country from the customers sheet
- Pulled coffee type, roast type, size, and unit price from the products sheet
- Created sales column (Unit Price × Quantity)
- Formatted date and currency fields consistently
- Checked and removed duplicate records

### 2. Analysis Performed

- Total sales over time broken down by coffee type (Arabica, Excelsa, Liberica, Robusta)
- Country-wise revenue comparison
- Top 5 customers by total spend
- Segmentation by roast type, package size, and loyalty card status

### 3. Dashboard Development

- Built PivotTables for each visualization
- Created a dynamic line chart for sales trends over time
- Added bar charts for country and customer comparisons
- Implemented timeline slicer for date range filtering
- Added slicers for Roast Type, Size, and Loyalty Card
- Applied a consistent purple color theme for a professional presentation

<br>

## 💡 Key Insights

### 1. Sales Trends (2019–2022)

- **Liberica** shows the highest individual sales spikes (peaks near **$500**)
- **Arabica** and **Excelsa** maintain consistent mid-range performance throughout
- **Robusta** remains the lowest performer across the entire period
- Sales show seasonal fluctuation with irregular spikes across all coffee types

### 2. Country Performance

| Country | Total Sales |
|---------|------------|
| 🇺🇸 United States | $16,465 |
| 🇮🇪 Ireland | $3,567 |
| 🇬🇧 United Kingdom | $886 |

- **United States** dominates with **78%** of total revenue
- **Ireland** is a strong secondary market at **17%**
- **UK** is an emerging market with significant growth potential

### 3. Top 5 Customers

| Customer | Total Spend |
|----------|------------|
| Brenn Dundredge | $307 |
| Brice Romera | $246 |
| Ailey Brash | $207 |
| Lacee Tanti | $205 |
| Elysee Sketch | $205 |

- Top customer spends **25% more** than the average of the remaining top 5
- Bottom 4 customers show nearly identical spend (~$205), suggesting a natural spending ceiling

### 4. Segmentation Insights

- **Roast Type**: Dark, Light, and Medium, all available for dynamic filtering
- **Size Options**: 0.2kg, 0.5kg, 1.0kg, 2.5kg — larger sizes likely drive higher per-order value
- **Loyalty Card**: Both Yes/No segments tracked — useful for retention analysis

<br>

## 🎯 Business Recommendations

- **Double down on the US market** — 78% revenue share makes it the highest priority for retention campaigns
- **Grow Ireland operations** — Strong secondary market worth targeted investment
- **Promote Liberica** — Highest revenue spikes suggest strong demand when available
- **Loyalty program expansion** — Use loyalty card slicer insights to measure impact and push adoption
- **Investigate UK underperformance** — Only $886 in sales suggests untapped potential or distribution gap
- **Retain top customers** — Brenn Dundredge and Brice Romera are VIP segments worth personalized outreach

<br>

## Dashboard Features

✅ **Timeline Slicer** — Filter by any custom date range (2019–2022)

✅ **Roast Type Filter** — Dark, Light, Medium

✅ **Size Filter** — 0.2kg, 0.5kg, 1.0kg, 2.5kg

✅ **Loyalty Card Filter** — Yes / No

✅ **Sales Over Time** — Multi-line chart by coffee type

✅ **Sales By Country** — Horizontal bar chart with USD labels

✅ **Top 5 Customers** — Bar chart with individual spend values

<br>

## Skills Demonstrated

- XLOOKUP and INDEX-MATCH for multi-sheet data merging
- PivotTables and PivotCharts for dynamic analysis
- Timeline and slicer implementation
- Multi-sheet workbook management
- Data cleaning and transformation
- Dashboard layout and visual design
- Business insight generation from raw transactional data

<br>

## How to Use

1. Download the Excel dashboard file
2. Enable macros/content if prompted
3. Use the slicers to filter data by:
   - Date Range (Timeline)
   - Roast Type
   - Package Size
   - Loyalty Card Status
4. Explore interactive charts to gain insights

<br>

## Author

**Mitali Padave**

[LinkedIn] https://www.linkedin.com/in/mitali-padave-581a2a242/

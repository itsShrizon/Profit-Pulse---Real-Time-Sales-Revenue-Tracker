
# 📊 Profit Pulse

A **comprehensive Power BI dashboard** for tracking and analyzing sales revenue, profits, transactions, and product performance across regions, countries, and sales representatives.

![Profit Pulse Dashboard](https://github.com/itsShrizon/Profit-Pulse---Real-Time-Sales-Revenue-Tracker/blob/main/Dashboard.png)
 <!-- Replace with the correct image path -->

## Overview
**Profit Pulse** provides a visually rich dashboard that presents key sales metrics, enabling users to monitor revenue trends, analyze profitability by region and product, and assess sales representatives' performance. The dashboard supports data-driven decision-making, ideal for stakeholders who need a quick and thorough overview of sales performance.

## Features
- **Total Revenue, Profit, and Transactions**: High-level financial metrics at a glance
- **Revenue Breakdown by Region and Gender**: Visualizes revenue distribution across regions and demographic segments
- **Profit by Region**: Compares profit margins across different regions
- **Revenue Analysis by Country**: Insights into revenue trends and average revenue per country
- **Revenue and Profit by Product**: Highlights product category performance (e.g., Smartphones, Laptops)
- **Transactions by Country**: Tree map showing transaction volume by country
- **Sales Representative Performance**: Displays revenue and transaction count for each sales representative

## Filters
The dashboard includes various filters for refined data analysis:
- **Year**: Filter data by specific years (e.g., 2019, 2020)
- **Region**: Focus on Africa or Europe
- **Products**: Drill down by product categories (Accessories, Laptops, Smartphones, Tablets)
- **Rank Levels**: Narrow down by sales rep rank levels (Level 1 to Level 5)

## Data Insights
This dashboard provides actionable insights into:
- **Regional Sales Performance**: Identify revenue-driving regions and countries
- **Product Profitability**: Analyze which products yield the highest profits
- **Sales Team Effectiveness**: Determine top-performing sales reps based on revenue and transaction count

## Setup Instructions
1. **Data Import**: Import your sales data into Power BI. Ensure data structure matches the dashboard visuals.
2. **Data Source Configuration**: Set up your data source for automatic refreshes based on your needs.
3. **Filter Customization**: Tailor filters (Year, Region, Products, Rank Levels) to meet your analysis requirements.

## Requirements
- **Power BI Desktop**: Download Power BI to use and customize the dashboard.
- **Data File**: A dataset with columns for:
  - Revenue
  - Profit
  - Transaction count
  - Region
  - Country
  - Product category
  - Sales representative
  - Additional relevant metrics

## Usage
1. Open the Power BI file.
2. Use filters on the left panel to adjust the data displayed.
3. Hover over or interact with visualizations for more detailed insights.

## Customization
Feel free to personalize visuals, filters, and layout to suit your organization’s needs. Add new charts or KPIs based on additional data as required.

### Explanation:
- **Sales Data Import**: The entry point where sales data is uploaded into Power BI.
- **Power BI Data Source**: Data is stored in Power BI and is used to build models and visuals.
- **Filters**: Filters allow users to drill down into specific segments of data by Year, Region, Product, and Rank Levels.
- **Data Model & Transformations**: Transform data as needed for visualization and analytics.
- **Dashboard Visuals**: Different types of visualizations display key metrics and insights.
- **Insights & Analysis**: The output where users can derive insights from the dashboard’s visualizations.

This flow helps visualize how data progresses through each stage of the dashboard setup, from import to actionable insights.

```mermaid
graph TD
    A[Sales Data Import] -->|Upload CSV/Excel| B[Power BI Data Source]
    B --> C{Filters}
    
    C -->|Filter by Year| D1[Year Filter]
    C -->|Filter by Region| D2[Region Filter]
    C -->|Filter by Products| D3[Product Filter]
    C -->|Filter by Rank Levels| D4[Rank Levels Filter]
    
    B --> E[Data Model & Transformations]
    
    E --> F{Dashboard Visuals}
    
    F -->|Total Revenue, Profit, and Transactions| G1[Financial Metrics Cards]
    F -->|Revenue by Region & Gender| G2[Pie Charts]
    F -->|Profit by Region| G3[Donut Chart]
    F -->|Revenue Analysis by Country| G4[Bar Chart]
    F -->|Revenue & Profit by Product| G5[Column Chart]
    F -->|Transactions by Country| G6[Tree Map]
    F -->|Sales Rep Performance| G7[Table View]
    
    G1 --> H[Insights & Analysis]
    G2 --> H
    G3 --> H
    G4 --> H
    G5 --> H
    G6 --> H
    G7 --> H

# Sales Performance Dashboard – Power BI

## Overview

An interactive Power BI dashboard built to turn raw transactional sales data into self-service analytics. It consolidates customer, product, and regional performance data into a single view, enabling faster, data-driven decision-making across teams.

## Business Objective

Provide a single source of truth for sales performance — helping stakeholders identify top-performing products, underperforming regions, low-stock risks, and customer loyalty trends without relying on manual reporting.

Data Model

## Built on a relational data model with the following tables:


Sales – transactional-level sales records
Customers – customer details and regional mapping
Products – product/category master data and stock status
RegionalTargets – target vs. achieved amounts by region
Main – core measures table (DAX calculations)


## Key Measures (DAX)


Total Sales Amount
Total Customers
Average Order Quantity
Total Order Quantity
Achieved Amount vs. Target Amount


## Dashboard Sections

1. Sales Dashboard


KPI cards: Total Customers, Total Sales Amount, Average Order Quantity, Total Order Quantity
Sales Trend line chart across the reporting period
Slicers: Category, Sale Date (range), Customer Region


2. Product Performance


Category-wise Sales (bar chart and pie chart)
Stock Status Summary (High / Medium / Low) to flag inventory risk


3. Customer Insights


New vs. Returning Customers (gauge)
Customer Count by Region
Loyalty Score Distribution (histogram)


4. Regional Performance


Monthly Target Trends: Achieved vs. Target Amount over time
Targeted vs. Achieved Amount by Region


## Key Insights


All 4 regions beat sales targets by 11–15%
51% of SKUs flagged as low stock, surfacing a supply-risk signal for procurement
Loyalty score and regional breakdowns support targeted retention and expansion strategies


Tools & Techniques

Power BI · DAX · Data Modeling · Interactive Slicers/Filters · Smart Narratives

![dashboard](https://github.com/hitz04/Sales-Performance-Dashboard-/blob/main/Snapshot%20of%20dashboard%20.png)

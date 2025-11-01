---
title: "Farm Product Sales and Revenue Insights – Tableau Dashboard"
date: 2025-11-01
categories: [Projects, Tableau, Data Visualization]
tags: [Tableau, Dashboard, Farm, Sales Analysis, Revenue Insights]
description: >-
  An interactive Tableau dashboard analyzing farm product sales data. Explore total sales over time, product performance, regional sales, and revenue contribution to uncover actionable insights for inventory and marketing strategies.
---

## Project Overview  
This project visualizes farm product sales data using Tableau. The dashboard includes:  
- **Total sales over time** (line chart)  
- **Sales by product** (bar chart)  
- **Average price per product** (bar or scatter chart)  
- **Regional sales performance** (filled map, stacked bars, top products per region)  
- **Profit & quantity analysis** (scatter plot with trend line and outlier highlighting)  

The insights help identify **top‑selling products, peak demand periods, high‑performing regions, and high‑value transactions** to guide stock planning and marketing strategies.

---

## Objectives  
- Load and clean the farm sales dataset.  
- Ensure `FarmProduct`, `Region`, and `Date` fields are valid and consistent.  
- Create calculated fields such as `TotalAmount = QuantityKg * PricePerKg`.  
- Visualize key metrics using line charts, bar charts, scatter plots, and maps.  
- Identify actionable insights for product performance, regional trends, and revenue optimization.

---

## Tools & Techniques  
- **Tableau Public** for interactive dashboards and data visualization.  
- **Calculated Fields** for revenue and other metrics.  
- **Filters and Interactivity** for dynamic exploration of products, regions, and time.  
- **Key Metrics Analyzed:** Total sales, quantity sold, average price, regional performance, and high‑value transactions.

---

## Key Steps & Dashboard Highlights

### 1. Data Cleaning & Preparation
- Removed null or empty values in `FarmProduct` and `Region`.  
- Converted `Date` column to date type and verified consistency.  
- Created `TotalAmount` as `QuantityKg * PricePerKg`.

### 2. Dashboard Visualizations
- **Total Sales Over Time (Line Chart):** Shows seasonal trends in revenue.  
- **Sales by Product (Bar Chart):** Identifies top‑selling farm products.  
- **Average Price per Product (Bar/Scatter Chart):** Compares pricing across products.  
- **Regional Sales (Filled Map, Stacked Bars, Top 5 Products):** Highlights high‑performing regions and popular products.  
- **Profit & Quantity Analysis (Scatter Plot with Trend Line & Outliers):** Detects high‑volume vs high‑value transactions and overall revenue trends.

---

## Key Insights  
1. **Top revenue products:** Identify which farm products generate the most revenue.  
2. **Seasonal trends:** Certain months show peak sales, useful for inventory planning.  
3. **Regional performance:** Some regions lead product sales—focus marketing on underperforming areas.  
4. **High‑value transactions:** Large transactions stand out in the scatter plot, indicating potential bulk orders or high‑demand products.

---

Driven by data, defined by impact.  

👉 [**View the full dashboard on Tableau Public**](https://public.tableau.com/app/profile/grace.nganga/viz/FarmProductSalesandRevenueInsights/FarmProductSalesandRevenueInsights?publish=yes)


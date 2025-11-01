---
title: "Medicine Sales and Revenue Insights – Tableau Dashboard"
date: 2025-10-31
categories: [Projects, Tableau, Data Visualization]
tags: [Tableau, Dashboard, Pharmaceutical, Sales Analysis, Revenue Insights]
description: >-
  An interactive Tableau dashboard analyzing pharmaceutical sales data. Explore total sales by medicine, quantity sold over time, pharmacy performance, and revenue contribution by medicine to uncover actionable insights.
---

## Project Overview  
This project involves visualizing pharmaceutical sales data using Tableau. The dashboard includes:  
- **Total sales by medicine** (bar chart)  
- **Quantity sold over time** (line chart)  
- **Pharmacy location × medicine performance** (heatmap)  
- **Revenue contribution by medicine** (pie chart)  

The insights help identify **top-selling medicines, peak demand periods, and pharmacy performance**, providing guidance for stock planning and marketing strategies.

---

## Objectives  
- Load and clean the pharmaceutical sales dataset.  
- Ensure `Medicine`, `PharmacyLocation`, and `Date` fields are valid and consistent.  
- Create calculated fields such as `TotalRevenue = Quantity * PricePerUnit`.  
- Visualize key metrics using bar charts, line charts, heatmaps, and pie charts.  
- Identify actionable insights for medicine stocking, pharmacy performance, and revenue optimization.

---

## Tools & Techniques  
- **Tableau Public** for interactive data visualization and dashboard creation.  
- **Calculated Fields** for revenue and data transformations.  
- **Filters and Interactivity** for dynamic analysis across medicines, dates, and locations.  
- **Key Metrics Analyzed:** Total sales, quantity sold, pharmacy performance, and revenue contribution.

---

## Key Steps & Dashboard Highlights

### 1. Data Cleaning & Preparation
- Removed null or empty values in `Medicine` and `PharmacyLocation`.  
- Converted `Date` column to date type and verified consistency.  
- Created `TotalRevenue` field as `Quantity * PricePerUnit`.

### 2. Dashboard Visualizations
- **Total Sales by Medicine (Bar Chart):** Shows revenue ranking across all medicines.  
- **Quantity Sold Over Time (Line Chart):** Highlights seasonal demand and trends.  
- **Pharmacy Location × Medicine (Heatmap):** Identifies which pharmacies sell which medicines most.  
- **Revenue Contribution by Medicine (Pie Chart):** Displays which medicines drive the most revenue.

---

## Key Insights  
1. **Revenue leaders:** Amoxicillin generates the highest revenue, followed by Ibuprofen and Cough Syrup.  
2. **Quantity trends:** Amoxicillin consistently sells the most units over time. Paracetamol and Vitamin C have the lowest quantities sold.  
3. **Pharmacy performance:** Mombasa pharmacy leads in Amoxicillin sales, while Eldoret leads in Ibuprofen sales. Other locations have moderate sales across remaining medicines.  
4. **Revenue contribution:** Amoxicillin contributes the largest share of revenue, followed by Ibuprofen and Cough Syrup. Paracetamol and Vitamin C contribute the least.  

---

Driven by data, defined by impact.  

👉 [**View the full dashboard on Tableau Public**](https://public.tableau.com/app/profile/grace.nganga/viz/MedicineSalesandRevenueInsights/MedicineSalesandRevenueInsights?publish=yes)


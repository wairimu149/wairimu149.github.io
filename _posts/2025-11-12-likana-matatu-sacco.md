---
title: "Likana Matatu SACCO – Festive Season Data Analysis"
date: 2025-11-12
categories: [Projects, Data Analysis, Transport]
tags: [SQL, Python, Tableau, Matatu, Revenue, Occupancy, Bookings, Payments]
description: >-
  A synthetic dataset simulating a Kenyan matatu SACCO with multiple routes, seasonal pricing, bookings, cancellations, payment modes, and vehicle occupancy. Explore route performance, ticket sales, occupancy trends, revenue, and payment preferences to guide festive season planning and operational decisions.
---

## Project Overview  
This project involves creating a **synthetic matatu dataset** with 500 sample entries. The dataset includes:  
- **Routes** such as Eldoret-Nairobi, Nairobi-Mombasa, Thika, Nakuru, Kisumu  
- **Seasons** including Normal, Christmas, Jamhuri Day, Easter  
- **Ticket Prices** for normal and peak periods  
- **Booking Dates** and **Departure Dates**  
- **Bookings** including cancelled and successful tickets  
- **Mode of Payment**: MPESA, ATM, Cash  
- **Booking Channels**: Online, Agent, Walk-in  
- **Vehicles** with IDs and total seating capacity  

The analysis provides insights into: **route revenue, ticket success rates, occupancy trends, and payment distribution**, helping the SACCO plan operations during festive periods.

---

## Objectives  
- Create and simulate a matatu dataset to analyze operational and financial metrics.  
- Demonstrate data analysis skills including:
  - **Aggregations**: SUM, AVG, COUNT per route, day, or season  
  - **Time Analysis**: Revenue and bookings by departure date or month  
  - **Filtering**: Analyze data by season, route, or payment method  
- Generate actionable insights for SACCO operations and festive planning.

---

## Tools & Techniques  
- **Python / Pandas** for dataset generation and preprocessing  
- **Tableau** for visualization and interactive dashboards  
- **Key Metrics Analyzed:**  
  - Revenue per route and departure date  
  - Total successful and cancelled tickets  
  - Occupancy rates per route and day of week  
  - Payment mode distribution  
  - Monthly booking trends

---

## Key Steps & Analysis Highlights

### 1. Data Generation & Cleaning
- Created a synthetic dataset with 500 entries including routes, seasons, bookings, cancellations, and payments  
- Ensured realistic ticket prices, capacities, and occupancy rates  
- Verified data consistency and integrity

### 2. Data Analysis & Visualization
- **Total Revenue by Route:** Summed revenue for each route across seasons  
- **Revenue by Departure Date:** Identified peak travel dates  
- **Occupancy Trends:** Daily occupancy rates by route and season  
- **Monthly Successful Tickets:** Tracked booking trends over time  
- **Ticket Status by Route:** Compared cancelled vs successful tickets  
- **Payment Distribution:** Analyzed proportion of MPESA, ATM, and Cash payments  

---

## Key Insights  
1. **Revenue leaders:** Certain routes (e.g., Nairobi-Mombasa, Eldoret-Nairobi) generate the most revenue, especially during festive seasons.  
2. **Occupancy trends:** Weekends and festive periods show highest seat utilization; some weekdays are underbooked.  
3. **Ticket success rates:** Majority of tickets are successful; cancellations are concentrated around certain dates.  
4. **Payment patterns:** MPESA dominates as the preferred payment mode, followed by Cash and ATM.  
5. **Seasonal planning:** Christmas and Jamhuri Day see spikes in bookings and revenue, indicating need for extra vehicles and staff.

---

Driven by data, defined by impact.  

👉 [Access the Tableau Dashboard](https://public.tableau.com/app/profile/grace.nganga/viz/Book1_17472040523480/Dashboard1?publish=yes)



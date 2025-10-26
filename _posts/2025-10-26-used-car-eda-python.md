---
title: "Used Car Data Analysis – Python & EDA"
date: 2025-10-26
categories: [Projects, Python, Data Analysis]
tags: [Python, Pandas, EDA, Seaborn, Matplotlib, Data Cleaning]
description: >-
  A comprehensive Python-based analysis of used car data, including data cleaning, preparation, and exploratory data analysis to uncover key trends in price, mileage, and car features.
---

## Project Overview  
This project involves analyzing a dataset of used cars using Python. The analysis includes **data wrangling**, **preparation**, and **exploratory data analysis (EDA)** to uncover patterns in car price, mileage, age, and other features.  
👉 [**View the full notebook on Google Colab**](https://colab.research.google.com/drive/1dSfDJaQKTj2z2eVOlZWJLAG7UTELj3k7?usp=sharing)

---

## Objectives  
- Load and clean the used car dataset.  
- Transform string columns into numerical formats (e.g., `milage`, `horsepower`).  
- Create new features such as `car_age` for analysis.  
- Perform univariate and bivariate EDA using visualizations.  
- Identify meaningful insights about pricing, mileage, accident history, and fuel types.

---

## Tools & Techniques  
- **Python** with `pandas` for data cleaning and feature engineering.  
- **Matplotlib** and **Seaborn** for visualizations and exploratory analysis.  
- **Regex** for extracting numeric values from complex columns like `engine`.  
- **Key Features Analyzed:** Mileage, price, model year, accident history, fuel type, and horsepower.

---

## Key Steps & Code Highlights

### 1. Data Cleaning & Preparation
- Converted `milage` from strings like `"51,000 mi."` to integers.  
- Converted `accident` column to binary (1 = accident reported, 0 = none).  
- Created a `car_age` column as `current_year - model_year`.  
- Extracted `horsepower` from the `engine` column using regex and handled missing values with the median.

### 2. Exploratory Data Analysis
- **Univariate Analysis:**  
  - Histogram for `price` distribution.  
  - Boxplot to identify outliers in `milage`.  
- **Bivariate Analysis:**  
  - Scatter plot for `milage` vs `price`.  
  - Box plot for `price` vs `accident` history.  
  - Violin plot for `price` vs `fuel_type`.

---

## Key Insights  
1. **Price decreases with mileage**: Cars with higher mileage generally have lower resale value.  
2. **Accident history impacts value**: Cars with reported accidents have lower median prices than those without accidents.  
3. **Fuel type matters**: Electric and hybrid cars tend to maintain higher prices compared to petrol or diesel cars.  

---

Driven by data, defined by impact.


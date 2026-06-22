# Walmart-Sales-Analysis-Dashboard

<img width="275" height="183" alt="Image" src="https://github.com/user-attachments/assets/d4afea2a-adbc-47b7-9105-78779e4a3696" />




# Walmart Store Sales Analysis Dashboard

## Project Overview

This project analyzes Walmart store sales data using Microsoft Excel and Power BI.

The goal of the project was to identify sales trends, evaluate store performance, examine holiday effects, and investigate whether environmental and economic factors such as Temperature, CPI, and Fuel Price influence weekly sales.

The analysis was conducted using Pivot Tables, Regression Analysis, Statistical Techniques, and Interactive Dashboard Visualizations.

---

# Dataset Information

**Dataset:** Walmart Store Sales Dataset

The dataset contains weekly sales records for Walmart stores between 2010 and 2012.

### Variables Included

* Store
* Date
* Weekly Sales
* Holiday Flag
* Temperature
* Fuel Price
* CPI
* Unemployment Rate

---

# Key Performance Indicators (KPIs)

* **Total Sales:** $6.74 Billion
* **Average Weekly Sales:** $1.05 Million
* **Number of Stores:** 45

These KPIs provide a summary of Walmart's overall sales performance across all stores included in the dataset.

---

# Research Questions

### 1. What are the best and worst months and quarters for Walmart stores?

Monthly and quarterly sales were analyzed to determine periods of highest and lowest sales performance.

### 2. What are the stores which record the highest quarter and annual sales growth?

An initial attempt was made to analyze annual sales growth. However, because the dataset only contains data up to October 26, 2012, annual growth calculations would be incomplete and potentially misleading. Therefore, annual growth findings were not included in the final analysis.

### 3. What is the impact of Temperature, CPI, and Fuel Price on weekly sales?

Multiple Linear Regression was performed to determine whether these variables significantly influence weekly sales.

### 4. Which stores had the highest sales?

Store-level sales were aggregated and compared to identify the highest-performing Walmart stores.

### 5. How do holiday weeks compare to non-holiday weeks in terms of average weekly sales?

Average weekly sales during holiday and non-holiday periods were compared to determine the effect of holidays on sales performance.

### 6. How do holiday and non-holiday periods affect average weekly sales across Walmart stores?

Average weekly sales were analyzed by both Store and Holiday Status to identify how holiday periods influence sales performance at different Walmart locations.

---

# Tools Used

## Microsoft Excel

* Data Cleaning
* Pivot Tables
* Regression Analysis
* Statistical Analysis

## Power BI

* KPI Cards
* Interactive Dashboard
* Data Visualization
* Slicers and Filtering

---

# Methodology

## Monthly and Quarterly Sales Analysis

Pivot Tables were used to aggregate sales by Month and Quarter.

Column charts were created to visualize sales performance over time and identify seasonal trends.

---

## Store Sales Analysis

Weekly sales were aggregated by Store using Pivot Tables and Power BI visualizations.

This analysis was used to identify stores with the highest overall sales performance.

---

## Holiday Sales Analysis

Average weekly sales were compared between Holiday and Non-Holiday periods.

Sales performance was also analyzed across stores to determine how holiday periods influenced store-level sales.

---

## Holiday Regression Analysis

A Simple Linear Regression model was developed using:

### Dependent Variable

* Weekly Sales

### Independent Variable

* Holiday Flag

### Results

* **R² = 0.0014**
* **Significance F = 0.0030**

The model was statistically significant, indicating that holiday status has a measurable effect on weekly sales.

---

## Temperature, CPI and Fuel Price Analysis

A Multiple Linear Regression model was developed using:

### Dependent Variable

* Weekly Sales

### Independent Variables

* Temperature
* Fuel Price
* CPI

### Regression Results

* **R² = 0.0080**
* **Significance F = 3.48 × 10⁻¹¹**

### Variable Significance

| Variable    | P-Value  | Significant |
| ----------- | -------- | ----------- |
| Temperature | 0.000029 | Yes         |
| Fuel Price  | 0.588819 | No          |
| CPI         | 0.000001 | Yes         |

---

# Key Findings

## Monthly and Quarterly Performance

* Sales performance varied across months and quarters.
* Some quarters consistently generated stronger sales than others.
* Seasonal patterns were observed throughout the dataset.

---

## Store Performance

* Sales performance differed significantly across Walmart stores.
* Several stores consistently generated substantially higher sales than others.
* Store-level analysis identified the highest-performing stores within the dataset.

---

## Holiday Effects

* Holiday weeks generally recorded higher average weekly sales than non-holiday weeks.
* Holiday status was found to be statistically significant in the regression analysis.
* Holidays can therefore be considered an important contributor to sales performance.

---

## Impact of Temperature, CPI and Fuel Price

* Temperature was statistically significant (p < 0.05).
* CPI was statistically significant (p < 0.05).
* Fuel Price was not statistically significant (p > 0.05).

Although Temperature and CPI were statistically significant predictors, the model's explanatory power was very low.

The regression model produced an **R² value of 0.008**, meaning that less than 1% of the variation in weekly sales can be explained by Temperature, CPI, and Fuel Price.

This suggests that other factors not included in the dataset likely play a much larger role in influencing sales performance.

---

# Dataset Limitations

The dataset contains records from:

* 2010
* 2011
* Part of 2012

The year 2012 contains data only up to **October 26, 2012**.

Because the final year is incomplete, annual growth calculations would not provide a fair comparison with previous years. Therefore, annual growth findings were excluded from the final analysis.

---

# Dashboard Features

The Power BI dashboard includes:

* Total Sales KPI
* Average Weekly Sales KPI
* Number of Stores KPI
* Monthly Sales Analysis
* Quarterly Sales Analysis
* Store Sales Analysis
* Holiday Sales Analysis
* Holiday vs Non-Holiday Store Comparison
* Temperature vs Weekly Sales Analysis
* CPI vs Weekly Sales Analysis
* Interactive Store Slicer

---

# Conclusion

This project demonstrates how Microsoft Excel and Power BI can be used together to perform business intelligence, statistical analysis, and data visualization.

The analysis revealed that sales performance varies across months, quarters, stores, and holiday periods. Holiday weeks generally produced stronger sales performance than non-holiday weeks.

Regression analysis identified Temperature and CPI as statistically significant predictors of weekly sales, while Fuel Price was not statistically significant. However, the low R² values obtained from the regression models indicate that additional variables not included in the dataset likely have a greater influence on sales performance.

If you have any questions, you can reach me through my emai:kashari.ia.101@gmail.com  ,thank you.

Overall, the project successfully provides insights into Walmart sales trends and demonstrates practical applications of data analytics techniques using Excel and Power BI.

# Walmart-Sales-Analysis-Dashboard

<img width="275" height="183" alt="Image" src="https://github.com/user-attachments/assets/d4afea2a-adbc-47b7-9105-78779e4a3696" />




## Project Overview

This project analyzes Walmart store sales data using Microsoft Excel and Power BI.

The objective was to identify sales trends, evaluate store performance, examine the effects of holidays, and investigate whether economic and environmental factors such as Temperature, CPI, and Fuel Price influence weekly sales.

The analysis was performed using Pivot Tables, Regression Analysis, Data Visualization, and Interactive Dashboards.

---

## Dataset Information

Dataset: Walmart Store Sales Dataset

Variables included:

* Store
* Date
* Weekly Sales
* Holiday Flag
* Temperature
* Fuel Price
* CPI
* Unemployment Rate

The dataset contains weekly sales records for multiple Walmart stores between 2010 and 2012.

---

## Research Questions

### 1. What are the best and worst months and quarters for Walmart stores?

Monthly and quarterly sales were analyzed using Pivot Tables and visualizations to identify periods of highest and lowest sales performance.

### 2. What are the stores which record the highest quarter and annual sales growth?

An initial attempt was made to analyze annual sales growth. However, the dataset only contains data up to October 26, 2012, making annual growth calculations unreliable. As a result, annual growth findings were not included in the final analysis.

### 3. What is the impact of Temperature, CPI, and Fuel Price on weekly sales?

Multiple Linear Regression was used to determine whether these variables significantly influence weekly sales.

### 4. What is the effect of holidays on sales?

Holiday and non-holiday sales were compared to determine whether holidays influence Walmart's weekly sales performance.

### 5. Which stores had the highest sales?

Store-level sales were aggregated and compared to identify the highest-performing Walmart stores.

---

## Tools Used

### Microsoft Excel

* Data Cleaning
* Pivot Tables
* Regression Analysis
* Statistical Analysis

### Power BI

* KPI Cards
* Interactive Dashboard
* Data Visualization
* Slicers and Filtering

---

## Methodology

### Sales Performance Analysis

Pivot Tables were used to aggregate sales by:

* Month
* Quarter
* Store
* Holiday Status

### Store Sales Analysis

Weekly sales were aggregated by store using Pivot Tables and Power BI visualizations. The results were used to identify stores with the highest overall sales performance.

### Regression Analysis

Multiple Linear Regression was performed using:

**Dependent Variable**

* Weekly Sales

**Independent Variables**

* Temperature
* Fuel Price
* CPI

Regression Results:

* R² = 0.0080
* Significance F = 3.48 × 10⁻¹¹

Variable Significance:

| Variable    | P-Value  | Significant |
| ----------- | -------- | ----------- |
| Temperature | 0.000029 | Yes         |
| Fuel Price  | 0.588819 | No          |
| CPI         | 0.000001 | Yes         |

Additional regression analysis was conducted to evaluate the effect of holidays on weekly sales.

---

## Key Findings

### Monthly and Quarterly Performance

* Sales varied across months and quarters.
* Q2 and Q3 recorded the highest sales performance.
* Q1 recorded the lowest overall sales.

### Store Performance

* Sales performance varied significantly across stores.
* Several stores consistently generated substantially higher weekly sales than others.
* Store-level analysis helped identify the highest-performing Walmart stores in the dataset.

### Holiday Effects

* Holiday weeks produced higher average sales than non-holiday weeks.
* Regression analysis also showed that holiday status was statistically significant.
* Holiday periods can therefore be considered important sales drivers.

### Economic and Environmental Factors

* Temperature and CPI were statistically significant predictors of weekly sales.
* Fuel Price was not statistically significant.
* Despite statistical significance, the model explained less than 1% of the variation in weekly sales (R² = 0.008), indicating that additional factors not included in the dataset likely play a much larger role in influencing sales.

---

## Dataset Limitation

The dataset covers:

* 2010
* 2011
* Part of 2012

The year 2012 contains data only up to October 26, 2012.

Because 2012 is incomplete, year-to-year comparisons and annual growth calculations may be biased and should be interpreted with caution. For this reason, annual growth findings were not included in the final analysis.

---

## Dashboard Features

The Power BI dashboard includes:

* Total Sales KPI
* Average Weekly Sales KPI
* Number of Stores KPI
* Monthly Sales Analysis
* Quarterly Sales Analysis
* Store Sales Analysis
* Holiday Sales Analysis
* Temperature vs Weekly Sales Analysis
* CPI vs Weekly Sales Analysis
* Interactive Store Slicer

---

## Conclusion

The analysis shows that Walmart sales are influenced by seasonal patterns, store-level differences, and holiday periods.

Regression analysis identified Temperature and CPI as statistically significant predictors of weekly sales, while Fuel Price was not statistically significant. However, the low R² value suggests that additional variables would be needed to build a strong predictive sales model.

Store-level analysis also revealed substantial differences in sales performance between Walmart locations, with some stores consistently outperforming others.

Overall, the project demonstrates how Excel and Power BI can be used together to perform business intelligence, statistical analysis, and dashboard development.


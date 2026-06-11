# Predictive-Analysis

## Project Overview

This project focuses on forecasting future chocolate sales using historical sales data. The objective was to analyze sales trends, identify seasonal patterns, and build a predictive model to support data-driven business decisions.

## Problem Statement

Businesses rely on accurate sales forecasts for inventory planning, demand forecasting, and resource allocation. This project uses historical chocolate sales data to predict future sales trends.

## Dataset

The dataset contains:

- Sales Person
- Country
- Product
- Date
- Amount
- Boxes Shipped

A total of 32 months of sales data was analyzed.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Jupyter Notebook

## Project Workflow

### 1. Data Cleaning
- Converted Date column to datetime format
- Cleaned Amount column by removing currency symbols and commas
- Converted sales values to numeric format

### 2. Exploratory Data Analysis
- Analyzed monthly sales trends
- Identified seasonal sales patterns
- Visualized historical sales performance

### 3. Data Quality Investigation
During analysis, several months showed zero sales values.

Further investigation revealed that these values likely represented missing observations rather than actual business activity.

These anomalous records were removed before model training to improve forecast reliability.

### 4. Predictive Modeling
Two forecasting approaches were explored:

#### Linear Regression
- Built an initial regression model
- Evaluated using MAE and R² Score
- Observed poor performance due to seasonal sales behavior

#### Holt-Winters Exponential Smoothing
- Applied a time-series forecasting model
- Captured seasonal patterns more effectively
- Generated realistic future sales forecasts

## Forecast Results

Predicted Sales:

| Forecast Period | Predicted Sales |
|---------------|---------------:|
| Month 1 | 1,048,342 |
| Month 2 | 829,311 |
| Month 3 | 887,609 |

## Key Insights

- Historical sales exhibit recurring seasonal patterns.
- Data quality significantly impacts forecasting accuracy.
- Time-series models outperform simple regression for seasonal sales data.
- Forecasts can support inventory planning and demand management.

## Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Time Series Analysis
- Forecasting
- Model Evaluation
- Business Insight Generation
- Data Visualization

## Future Improvements

- Apply ARIMA and SARIMA models
- Incorporate holiday and promotion effects
- Evaluate multiple forecasting techniques
- Build an interactive dashboard using Power BI

## Author

Deepika

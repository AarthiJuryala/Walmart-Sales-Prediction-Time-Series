# Walmart Sales Forecasting using Time Series Analysis

## Overview
This project analyzes and forecasts Walmart’s weekly sales using time series techniques. The goal is to identify patterns in historical data and build models that can support inventory planning and demand forecasting.

## Objective
- Analyze weekly sales data across multiple stores  
- Identify trends and seasonality  
- Build forecasting models using ARIMA and SARIMA  
- Evaluate model performance using standard metrics  

## Dataset
The dataset includes the following features:
- Store: Store ID  
- Date: Weekly timestamp  
- Weekly_Sales: Sales for each week  
- Temperature: Recorded temperature  
- Fuel_Price: Fuel cost  
- CPI: Consumer Price Index  
- Unemployment: Unemployment rate  
- Holiday_Flag: Indicator for holiday weeks  

## Exploratory Data Analysis
- Sales show clear seasonal patterns, especially during holidays  
- Noticeable variation across stores  
- External factors such as temperature and CPI have weak correlation with sales  
- Holiday periods consistently drive higher sales  

## Modeling
Two time series models were used:

### ARIMA
- Captures trends in non-seasonal time series data  

### SARIMA
- Extends ARIMA by incorporating seasonality  
- Better suited for retail sales patterns  

## Model Evaluation
Models were evaluated using:
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  

SARIMA performed better due to its ability to capture seasonal patterns.

## Forecasting
The final model was used to generate future sales forecasts. The predictions capture overall trends and seasonal variations and can support business planning.

## Business Insights
- Strong seasonal demand suggests the need for proactive inventory planning  
- Store-level performance varies, indicating scope for targeted strategies  
- External economic factors have limited impact compared to internal trends  
- Forecasting can help reduce stockouts and overstocking  

## Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Statsmodels  
- Scikit-learn  

# Walmart 45 Stores Time Series Analysis

## Overview

This repository contains the analysis of time series data for 45 Walmart stores. The goal of the project was to forecast sales and identify trends using advanced time series models, namely ARIMA (AutoRegressive Integrated Moving Average) and SARIMAX (Seasonal AutoRegressive Integrated Moving Average with Exogenous Variables).

The dataset represents the sales data for various products at 45 Walmart stores over time. The analysis explores the patterns in sales and attempts to forecast future sales to support inventory management, marketing strategies, and operational decisions.

## Dataset

The dataset used in this analysis consists of the following key columns:

- **Store**: The store ID (1–45).
- **Date**: The date of the sales record.
- **Weekly_Sales**: Sales figures for each week.
- **Holiday_Flag**: A flag indicating whether a particular week was affected by a holiday.
- **Temperature**: Weekly temperature in the region.
- **Fuel_Price**: Weekly fuel price.
- **CPI**: Consumer Price Index for the region.
- **Unemployment**: Weekly unemployment rate in the region.

## Models Used

- **ARIMA**: Used for time series forecasting to model the relationship between a series and its own past values.
- **SARIMAX**: An extension of ARIMA that also incorporates seasonal components and exogenous variables (like temperature, fuel price, CPI, etc.).

### Key Steps in the Analysis:
1. **Data Preprocessing**: The data was cleaned and transformed to handle missing values, outliers, and necessary feature engineering.
2. **Exploratory Data Analysis (EDA)**: Analyzed the dataset to understand trends, seasonality, and key factors influencing sales.
3. **Model Selection**: ARIMA and SARIMAX models were selected based on the characteristics of the data (e.g., seasonality, trends).
4. **Model Training and Forecasting**: Trained both models using historical sales data to generate forecasts for future sales.
5. **Model Evaluation**: Evaluated the model's accuracy using various metrics like RMSE and MAE to compare the performance of ARIMA and SARIMAX.

## Repository Structure

- **Walmart_Sales_Dataset**: Contains the raw dataset used for the analysis.
- **Walmart_Analysis.ipynb**: Jupyter notebook containing the entire analysis, including data preprocessing, model implementation, and results.
- **README.md**: This file, providing an overview of the project.
- **requirements.txt**: List of required Python packages to run the analysis (e.g., pandas, numpy, statsmodels, matplotlib, etc.).

 
### Clone the repository:

   ```bash
   git clone https://github.com/ArigalaAdarsh/Walmart-Analysis.git
  ```
### Conclusion
- This time series analysis using ARIMA and SARIMAX models provides insights into the sales patterns of 45 Walmart stores. By forecasting future sales, businesses can make data-driven decisions for inventory management, promotions, and staffing. The findings can help Walmart optimize its operations and improve sales performance

# The-Price-of-Gold-Time-Series-Insights-and-Future-Predictions


## Introduction 

 This project is a comprehensive exploration of forecasting gold prices using three time series models. The dataset covers daily gold prices in USD from 1950-01 to 2020-07.

## 🗂️ Dataset

- **Source**: Kaggle Dataset
- **Structure**: 847 observations with columns `Date` and `Price`.

  ## 🔧 Methodology

Three models were built and compared:

1. **Linear Regression**:
   - Performance metric: Mean Absolute Percentage Error (MAPE).

2. **Naive Forecasting**:
   - Utilizes the last observed value.

3. **Exponential Smoothing**:
   - Incorporates `statsmodels` for smoothing trends.
  

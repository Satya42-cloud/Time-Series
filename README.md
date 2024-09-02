# Time-Series
## Exchange Rate Forecasting with ARIMA and Exponential Smoothing

### Overview
This repository provides a comprehensive analysis and forecasting approach for exchange rate data using ARIMA and Exponential Smoothing techniques. Utilizing the exchange_rate.csv dataset, which includes historical exchange rates of USD to the Australian Dollar, this project demonstrates data preprocessing, model building, and performance evaluation to predict future exchange rates.

### Dataset
- Filename: exchange_rate.csv
- Description: Contains historical exchange rates with columns for date and USD to Australian Dollar exchange rates.
  
### Data Preparation and Exploration
- Loading Data: Import and parse date columns.
- Exploration: Plot time series to understand trends, seasonality, and anomalies.
- Preprocessing: Handle missing values and anomalies.

### Model Building - ARIMA
- Parameter Selection: Use ACF and PACF plots to determine ARIMA parameters.
- Model Fitting: Fit ARIMA model and analyze residuals.
- Forecasting: Generate and visualize forecasts against actual values.

### Model Building - Exponential Smoothing
- Model Selection: Choose between Simple, Holt’s Linear, or Holt-Winters models.
- Parameter Optimization: Optimize smoothing parameters using grid search or AIC.
- Model Fitting and Forecasting: Fit the model and compare forecasts with actual data.

### Evaluation and Comparison
- Error Metrics: Compute MAE, RMSE, and MAPE to evaluate forecast accuracy.
- Model Comparison: Discuss the performance, advantages, and limitations of ARIMA and Exponential Smoothing models.
- Conclusion: Summarize findings and insights on the best-performing model(s).

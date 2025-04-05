# 🌡️ Monthly Temperature Forecasting with ARMA 📈

Welcome to the **Monthly Temperature Forecasting** project! 🔍  
This project uses the **ARMA (AutoRegressive Moving Average)** model to predict future monthly temperatures based on historical climate data. Perfect for data science enthusiasts, researchers, or anyone curious about climate trends! 🌍

Dataset Source: https://zenodo.org/records/10951538/files/arima_temp.csv
---

## 📚 Project Overview

This notebook-driven project includes:

-  **Exploratory Data Analysis**
-  **Preprocessing & Stationarity Checks**
-  **Seasonal Decomposition**
-  **Model Identification (AR & MA orders)**
-  **Model Evaluation (Normality, Autocorrelation, Heteroskedasticity)**
-  **Forecasting with Confidence Intervals**
---

## 📈 Visual Insights
### Seasonal Decomposition
Breaks down the temperature into trend, seasonality, and residuals 🔍


### ADF Test
✔️ The series is stationary — essential for ARMA modeling.

### PACF & ACF Analysis
Used for identifying optimal AR(p) and MA(q) orders.

### Residual Diagnostics
Residuals behave like white noise, indicating a good model fit.

## 🔍 Final Model Selection
After comparing multiple ARIMA structures, the best model was:
**ARIMA(4, 0, 2)** (ARMA with no differencing)

It had the lowest:
- AIC
- BIC
- Residual error
- Better performance in normality and independence tests



📜 Credit: https://filippomb.github.io/python-time-series-handbook/notebooks/05/arma_arima_sarima.html
---



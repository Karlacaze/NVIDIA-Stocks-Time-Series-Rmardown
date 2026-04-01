# Time Series Forecasting of TIIE (28-Day Rate)

## Project Overview
This project analyzes and forecasts the short-term evolution of the 28-day Tasa de Interés Interbancaria de Equilibrio (TIIE), a key benchmark interest rate in the Mexican financial system. Given its relevance for financial markets, borrowing costs, and monetary policy analysis, accurate forecasting is essential.

The study compares different time series methodologies to determine which model provides the most reliable predictions.

---

## Objective
The main objective of this project is to identify the most accurate forecasting approach for the TIIE rate using time series techniques.

The analysis focuses on comparing:
- ARIMA (AutoRegressive Integrated Moving Average)
- ETS (Error, Trend, Seasonality – Exponential Smoothing)

---

## Dataset
The dataset consists of historical observations of the 28-day TIIE rate, covering recent macroeconomic fluctuations, including the increase and subsequent decline observed between 2022 and 2025.

The data is used for:
- Model estimation (training)
- Out-of-sample forecast evaluation

---

## Methodology

### ARIMA Model
The ARIMA model captures the stochastic structure of the time series through autoregressive and moving average components. It requires:
- Stationarity (achieved through differencing)
- Selection of optimal parameters (p, d, q)

This model is particularly useful for capturing complex temporal dependencies.

### ETS Model
The ETS model is based on exponential smoothing and decomposes the series into three components:
- Error (E)
- Trend (T)
- Seasonality (S)

The model automatically selects the optimal specification based on the data.

---

## Model Evaluation
Forecast accuracy is assessed using out-of-sample performance metrics:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

Lower values of these metrics indicate better predictive performance.

---

## Results and Insights
The TIIE exhibits a clear structural pattern, characterized by a significant increase followed by a gradual decline. Both models are capable of capturing these dynamics, although their performance depends on the underlying data structure.

ARIMA tends to provide better results when the series exhibits complex stochastic behavior, while ETS offers a more flexible and automated framework.

---

## Conclusion
There is no universally superior model for forecasting the TIIE. Model performance depends on the characteristics of the time series, including trend stability and structural changes.

This analysis highlights the importance of model selection in financial time series forecasting and its implications for decision-making under uncertainty.

---

## Technologies Used
- R

Libraries:
- forecast
- tseries
- ggplot2
- stats

---

## Team Members
- Laura Victoria Miquel Herrera  
- Karla Sofía Cantú Zendejas  
- Saúl Josué Ruiz González  
- Rodrigo Rivas González  

---

## How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/Karlacaze/NVIDIA-Stocks-Time-Series-Rmardown

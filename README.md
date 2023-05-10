# Google Stock Price Prediction

We will be analysing Google stock prices as well as making future predictions using the ARIMA Model.

Time Series Forecasting means analyzing and modeling time-series data to make future decisions. Some of the applications of Time Series Forecasting are weather forecasting, sales forecasting, business forecasting, stock price forecasting, etc. The ARIMA model is a popular statistical technique used for Time Series Forecasting.

## What is ARIMA?
**ARIMA** stands for **Autoregressive Integrated Moving Average.** It is an algorithm used for forecasting Time Series Data. ARIMA models have three parameters like ARIMA(p, d, q). Here p, d, and q are defined as:

- p is the number of lagged values that need to be added or subtracted from the values (label column). It captures the autoregressive part of ARIMA.
- d represents the number of times the data needs to differentiate to produce a stationary signal. If it’s stationary data, the value of d should be 0, and if it’s seasonal data, the value of d should be 1. d captures the integrated part of ARIMA.
- q is the number of lagged values for the error term added or subtracted from the values (label column). It captures the moving average part of ARIMA.

We will collect Google stock price data using the Yahoo Finance API. If you have never used Yahoo Finance API, you can learn more about it <a href="https://github.com/mknyambura/Get-Stock-Price-Data-using-Python">here.</a>

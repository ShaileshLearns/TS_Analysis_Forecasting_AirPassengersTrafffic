# To build a model to forecast the air passenger traffic for future months

### OBJECTIVE
We have a monthly time series data of the air passengers from 1 Jan 1949 to 1 Dec 1960. Each row contains the air passenger number for a month of that particular year. Objective is to build a model to forecast the air passenger traffic for future months.

## PROJECT

1. Importing the required libraries.
2. Importing data.
3. Exploratory Data Analysis of Time Series Data
    * Shape of the data
    * DataType of Columns
    * Descriptive Statistics
    * Checking for null values and handling them if any.
    * Analysind Trend, variance and Seasonaity of Time Series Data
    * Decompostion of Time Series (Trend, Seasonal, Residual Components)
4. Forecasting Methods Used : ARIMA, SARIMA, Exponential Smoothing (Single, Double, Triple)
    * For ARIMA : Stationary Test (Augmented Dickey-Fuller (ADF) Test), Differencing, ACF and PACF Correlation Plots, Auto Arima
6. Comparing different model performances and then chossing the most effective one.

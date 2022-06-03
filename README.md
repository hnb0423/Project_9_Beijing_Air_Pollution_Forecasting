# Project_9: Beijing Air Pollution Forecasting

## Business Problem 
The goal of this project is to utilize time series forecasting to predict level of PM2.5 in Beijing

## Data
UCI: https://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data

## Data processing 
Undersample hourly data to weekly and monthly data 
Replace missing values with weighted moving average
Box-cox transformation
Construct ACF, PACF plot 
Run ADF and KPSS test
Construct periodogram to study multi-seasonality

## Model Application
### Univariate Analysis
Simple time series models: naive, seasonal naive, drift, mean models
SARIMA model
Dynamic hamornic regression
TBATs model

### Multivariate Analysis
Regression with ARMA error
VAR model 


# Project_9: Beijing Air Pollution Forecasting

## Business Problem 
The goal of this project is to utilize time series forecasting to predict level of PM2.5 in Beijing.

## Data
UCI: https://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data

## Data processing & EDA
Undersample hourly data to weekly and monthly data <br/>
Replace missing values with weighted moving average <br/>
Box-cox transformation <br/>
Construct ACF, PACF plot <br/>
Run ADF and KPSS test <br/>
Construct periodogram to study multi-seasonality <br/>
Split data into train and test set

## Model Application
### Univariate Analysis
Simple time series models: naive, seasonal naive, drift, mean models <br/>
SARIMA model <br/>
Dynamic hamornic regression <br/>
TBATs model

### Multivariate Analysis
Regression with ARMA error<br/>
VAR model 


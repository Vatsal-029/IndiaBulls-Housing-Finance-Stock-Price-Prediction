# IndiaBulls-Housing-Finance-Stock-Price-Prediction
Using Time Series Analysis to predict stock open price for IndiaBulls HSG Finance
### Data source: https://in.finance.yahoo.com/quote/IBULHSGFIN.NS/history/
## Key Notes--
#### The data time range: 10-06-2019 to 09-06-2020
#### The data recorded has 245 rows and 7 variables including ['Date', 'Open', 'High', 'Low', 'Close', 'Volume'] and has only one missing row
### Variable details are specified in the file.
#### The variable used for time-series-analysis is : "Open"
#### Visualization is done on matplotlib.pyplot; other libraries used are - numpy, pandas, statsmodels, datetime, and itertools
#### Model used is "SARIMA" 
Seasonal Autoregressive Integrated Moving Average, SARIMA or Seasonal ARIMA, is an extension of ARIMA that explicitly supports univariate time series data with a seasonal component. It adds three new hyperparameters to specify the autoregression (AR), differencing (I) and moving average (MA) for the seasonal component of the series, as well as an additional parameter for the period of the seasonality.

# PES-IO
#ARIMA
Standa for Autoregressive Integrated Moving Average which is used as a forecasting tool to predict how something will act in the future based on past performance
Autoregression (AR): refers to a model that shows a changing variable
Integrated (I): indicates that the data values have been replaced with the difference between their values and the previous values
Moving average (MA):  incorporates the dependency between an observation and a residual error from a moving average model applied to lagged observations.

The model has 3 parameters:
1.p-The number of lag observations
2.d-The number of times that the observations are differenced
3.q- The size of the moving average window

#p and q is calculated by max of PACF and ACF
#d is calucated by differencing

#SARIMA
SARIMA models are similar to ARIMA but it takes specifically designed values to handle data with seasonal patterns.
It is an extension of ARIMA used to model seasonal time series
Command:SARIMA(p,d,q)x(P,D,Q,s)  

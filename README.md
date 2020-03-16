# Time-Series-Australian-Gas-Production

The aim of this exercise is to understand and explain Australian monthly gas production
time series and forecast the monthly production for the next 20 time periods using manual
and auto arima forecasting methods. 

The time series we will use for exercise purpose starts from January 1970 to August 1995.
We will create a training dataset to test our forecasts and eventually use them on the test dataset to ascertain the accuracy of our model. 

Thedataset ‘gas’ reside in the forecast package library in R which contains methods and tools for
displaying and analyzing univariate time series forecasts including exponential smoothing
via state space models and automatic ARIMA modelling.

The dataset is already stored as time series object which will allow us to immediately start
gaining insights and procure inferences. 

I will implement and explain the following steps through our process: 

#Components of the time series 
#Periodicity of dataset
Stationarity test.
Null and alternate hypothesis for the stationarity test 
De-seasonalise the series
Develop an initial forecast using both manual and auto.arima 
Reporting the accuracy.

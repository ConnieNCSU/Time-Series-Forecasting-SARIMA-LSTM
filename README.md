# Time-Series-Forecasting-SARIMA-LSTM
In this project I forecast a time series data (Monthly beer production) using ARIMA (Autoregressive Integrated Moving Average), LSTM (Long Short Term Memory Neural Network) with Python and inspect their results.

The evaluation results are shown as follows:

| Models | RMSE Errors | MSE Errors |
|----------|----------|----------|
| ARIMA| 4.557617 | 20.771869 |
| LSTM| 6.515349 | 42.449777 |


In conclusion, SARIMA has better performance on this forecasting task. 
The reason can be that SARIMA models work well with time series data that has a clear seasonal pattern and are less sensitive to the amount of data available. LSTM networks, on the other hand, require large amounts of data to train effectively and may not perform well on time series data with short seasonal patterns.

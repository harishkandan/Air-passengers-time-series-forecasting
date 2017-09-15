# Air-passengers-time-series-forecasting
Basic time series analysis and forecasting.

### The data
The available dataset is of the number of air passengers from 1949 to 1960 for every month.
The data exhibited both an increasing trend and seasonality.

### The model
Training has been done with an ARIMA model. Techniques like moving average and differencing were used to convert the available time series into a stationary time series. ACF and PACF was plotted and the appropriate values of p, d and q for ARIMA were found.
The final prediction had an RMSE of 52. 1841.

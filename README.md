# Auto-ARIMA-on-Sales
automatically apply the optimal order for an ARIMA model on product sales


Dealing with ARIMA Model:
1. Upload time series data
2. Plot the data and observe whether it is a stationary time series; for non-stationary time series, first d-order difference operation is performed to convert it into a stationary time series
3. After the second step, a stationary time series has been obtained. To obtain the autocorrelation coefficient ACF and the partial autocorrelation coefficient PACF of the stationary time series, the optimal rank p and order q can be obtained by analyzing the autocorrelation graph and the partial autocorrelation graph.

And this project will use the pipeline method of the pmdarima module to create the model optimized by best AIC,A standard for measuring the goodness of fit of statistical models.

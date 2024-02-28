# TimeSeries_StackingModels

This notebook is to predict the mean_temperature for the daily climate time series data. The data is available at:

https://www.kaggle.com/datasets/sumanthvrao/daily-climate-time-series-data

Here are methods I used in the notebook:

- SARIMAX: Seasonal ARIMA + exogenous variables.
- Prophet:
    - Univariate Prophet 
    - Univariate Prophet + XG Boost on the residuals
    - Univariate Prophet on differencing time series
    - Multivariate Prophet
- Vector error correction model (VECM)
- Long-short term memory (LSTM)
- Neural Prophet: Neural network version of Prophet.
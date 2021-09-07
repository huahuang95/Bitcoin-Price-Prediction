# Bitcoin-Price-Prediction
Bitcoin Price Forecasting Using Time Series Analysis

### Data Source
- [Bitcoin Historical Data](https://www.kaggle.com/mczielinski/bitcoin-historical-data)

### Project Objectives
- Develop time series models to predict Bitcoin price and evaluate models' performance.

### Language/Methods
- Double Exponential Smoothing Estimations
- ARIMA (Auto-Regressive Integrated Moving Average) Model
- XGBoost
- LSTM (Long short-term memory) Networks

### Project Summary
- Though the long short-term memory networks may not be ideal for forecasting turbulent markets like Bitcoin, compared with the other three models, the LSTM has the lowest test RMSE and the most effective performance in Bitcoin price prediction.
- The double exponential smoothing method has the second-lowest RMSE, however, the predicted result can only indicate an upward trend in the time interval of test data. In other words, it may not be able to capture the movement of each day, but it may provide a reliable result of suggesting a downward or an upward trend of price fluctuation.
- ARIMA and XGBoost models provide similar test RMSEs. Compared to the other models, these two models prove to be less effective when handling volatile data like Bitcoin prices.

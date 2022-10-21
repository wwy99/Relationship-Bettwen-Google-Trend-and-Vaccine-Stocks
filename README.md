# Relationship-Bettwen-Google-Trend-and-Vaccine-Stocks

Abstract
Background:
During the global pandemic coronavirus (Covid-19) outbreak in 2019, the world was shocked and in desperate need of a vaccine to overcome the disease. Nowadays and especially during the time of pandemic and quarantine, with the rapid development of the internet, a vast amount of data are being created every single day due to people’s high reliance on electronic devices. This shift in human society and lifestyle also creates an impact on the stock market which is highly correlated with information and sentiments. Google, as one of the biggest technology and internet company in the world, have tremendous users and data. Investigating the google trends of virus vaccines might provide a better insight into how the internet impacts the stock market.

Objective:
The objective is to predict the vaccine concept stocks with historical data and the google trend index.

Methods:
Google Trends data were obtained from the google trend website. Autoregressive integrated moving average (ARIMA) and long short-term memory (LSTM) models were used to predict the stock price of Novavax (NVAX) with historical price data. ARIMAX and multivariate LSTM were used to predict Novavax(NVAX) with historical data and google trends in comparison. All models were evaluated using forward chaining cross-validation, and root means square error (RMSE) was used as the performance metric.

Results:
The Autoregressive integrated moving average (ARIMA) with historical data predicted the stock price with an RMSE of 0.6038. The ARIMAX model with google trend of the keyword “Covid-19 Vaccine” as an exogenous predicted the stock price with RMSE of 0.4838. The LSTM with historical data predicted a stock price with an RMSE of 12.33. After adding the same google trend, the model predicted a stock price with an RMSE of 11.627.

Conclusion:
Search trends might be a decent index to interpret the market sentiment and predict the movement of the stock market.



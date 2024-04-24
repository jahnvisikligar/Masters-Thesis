
![BTCStocks (1)](https://user-images.githubusercontent.com/83291068/206888485-00107d88-5d26-4e27-8cdf-6ab8478e8379.jpg)

# Predictive analysis of Bitcoin stock price using ARIMA

My Master's thesis focuses on predicting of Bitcoin stock prices using the Time-Series forecast method.

## Idea
Predictions play a key role in the stock market industry and heavily rely on established methods like fundamental and technical analysis. However, they have not proven to be a dependable source of precise predictions. To find a method that could provide predictions that were close to the actual ones, there have been numerous studies on the subject. In order to comprehend and respond to the research questions as they are discussed below, I used the ARIMA model in this paper.

## Research questions:
* While there have been numerous methods used to implement stock market predictions (SMP). It is unclear whether the method is suitable for the specified application. What is the most effective technique for predicting the stock market?

* The information is crucial to this process. What procedures are followed in order to smooth the data before use?

* A model that is is needed to handle the difficulties of live SMP testing in an environment of market volatility and panic selling. While there have been attempts to address such events using different algorithms available on the market. But it remains difficult to determine the most effective strategy for dealing with this problem.

## Implementation
The cryptocurrency market, which is highly volatile, has seen the most rapid changes in recent years. Cryptocurrencies, unlike traditional stock prices, do not have a physical asset and vary depending on a variety of other factors. As a result, I intend to use the Kaggle dataset on cryptocurrency, which contains over 20+ cryptocurrencies' values from 2010 to 2018. I extracted data from all cryptocurrencies in order to save the values of Bitcoin stock prices. 

For my research, I used an ARIMA model with seasonality in the predicted values versus the actual values. I improved the ARIMA model with the SARIMAX model by including seasonality to reduce sudden spikes in predicted values. With the implementation of SARIMAX, the evaluation metrics - RMSE was improved by 24.57% (depending on the seasonal period).

## Technologies Used

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- StatsModels

# Stock Price Prediction

A stock market is the aggregation of buyers and sellers of stocks, which represent ownership claims on businesses; these may include securities listed on a public stock exchange, as well as stock that is only traded privately, such as shares of private companies which are sold to investors through equity crowdfunding platforms. Stock market data can be interesting to analyze and as a further incentive, strong predictive models can have a large financial payoff.

In this project, I have performed stock price prediction using Recurrent Neural Networks. The dataset was obtained from Kaggle. The data is the price history and trading volumes of the fifty stocks in the index NIFTY 50 from NSE India. The data spans from 1st January 2000 to 30th April 2021. I tried to predict the future Volume Weighted Average Price for the stocks, Reliance, TCS, HDFC & Bajaj Auto. I have used **simple RNN** and **LSTM** to predict the stock price for the next one and 10 days, using the previous few days' stock prices. For all the datasets I managed to achieve around **10<sup>-4</sup> Mean Squared Error** on the normalized values.

`DataSet`: [link](https://www.kaggle.com/datasets/rohanrao/nifty50-stock-market-data)

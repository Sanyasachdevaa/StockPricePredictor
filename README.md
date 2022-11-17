# StockPricePredictor

A stock or a share is a security that represents the ownership of a fraction of a corporation. This entitles the owner of a stock to a proportion to a company’s assets and profits equal to how much stock they own. Thus, being able to predict the prices of stocks is always a hot topic in both the Financial and Technical domains.

As concluded by Fama, financial time series prediction is known to be a difficult task due to a high level of noise and erratic volume. Back in 2003, Wang et al. applied ANN or Artificial Neural Networks on stock market price prediction and focused on volume, as a specific feature. One of the key findings by them was that the volume was not found to be effective in improving the forecasting performance. Ince and Trafalis targeted short term forecasting and applied SVM or Support Vector Machine model on stock price prediction. They found out that SVM outperformed MLP, while the result was also affected by trading strategies.

In this work, our objective is to build a prediction model for Closing Price Prediction, which focuses on predicting stock price trends over the next 60 days with fair accuracy. The stock/company upon which we based our research is Apple and we acquired more than 10 years of its stock prices from Yahoo!

Our model is based on the LSTM model or the Long Short-Term Memory, which is a kind of an Artificial Neural Network. We are using LSTM as unlike standard models, LSTM has feedback connections. LSTM are known to be very effective in sequence prediction problems because they are able to store past information that is important and forget information which isn’t important.

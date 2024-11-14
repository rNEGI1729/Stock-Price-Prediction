# Stock Price Prediction Using LSTM
This project demonstrates a time-series prediction model for stock prices using Long Short-Term Memory (LSTM) networks, a type of recurrent neural network (RNN). The model predicts future stock prices based on historical stock data, which is fetched using the yfinance library.

![image](https://github.com/user-attachments/assets/ffdd9c0f-665a-4b1b-a9b7-a37682d0bfac)


## Model Performance
The model’s performance is evaluated using the Root Mean Square Error (RMSE) metric. For this implementation, the RMSE value is approximately 2.05. Here’s what this means:

Interpretation: An RMSE of 2.05 indicates that, on average, the model’s predictions deviate by around 2.05 units from the actual stock prices.
Context: If the stock prices are around $100, this represents a ~2% deviation, which is relatively low. However, for stocks with much lower values, this error may be more significant.

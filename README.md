# Data Science Innovations in Financial Market Predictions
This project implements three different models (Transformers, LSTM, and GRU) to predict five different companies stock from yahoo finance like Apple, Google, Amazon, Sony and Netflix. This projects predicts closing stock prices using historical data and technical indicators. The model are trained on adjusted closing prices and various technical indicators to predict future stock movements.

# Overview
This project focuses on predicting the adjacent closing prices of stocks for Apple (AAPL), Amazon (AMZN), Netflix (NFLX), Sony (SONY), and Google (GOOGL). It uses three different models (Transformers, LSTM, and GRU) allowing users to compare their performance. The models are trained on historical data from 2012 to 2022, utilizing technical indicators like RSI and EMA to improve predictions.

# Objective
1. To predict the adjacent closing prices of selected stocks.
2. To compare the performance of three different models: Transformer, LSTM, and GRU.
3. To visualize and analyze the predictions using various plots and metrics.

# Input Data Format
The input data consists of historical stock prices retrieved from Yahoo Finance using the yfinance library. The data includes the following columns:

1. Date: The date of the stock price.
2. Open: The opening price on the given date.
3. High: The highest price during the trading session.
4. Low: The lowest price during the trading session.
5. Close: The closing price on the given date.
6. Adj Close: The adjusted closing price, accounting for splits and dividends.
7. Volume: The number of shares traded.

# Additional Features (Technical Indicators)
1. RSI: Relative Strength Index, calculated over a 15-day period.
2. EMA (Fast): Exponential Moving Average calculated over 20 days.
3. EMA (Medium): Exponential Moving Average calculated over 100 days.
4. EMA (Slow): Exponential Moving Average calculated over 150 days.
5. Target: Difference between the adjusted close and open prices, shifted by one day.
6. TargetClass: Binary classification target where 1 indicates a positive price movement, and 0 indicates a negative or no movement.
7. TargetNextClose: Adjusted closing price shifted by one day to serve as the prediction target.

# Common Parameters
Tcikers to use the dataset from yahoo finance:
import from yfinance 
tickers = ['AAPL', 'AMZN', 'NFLX', 'SONY', 'GOOGL']
Each of these tickers are used to download the dataset for the respective company.
1. 'AAPL' = Apple
2. 'AMZN' = Amazon
3. 'NFLX' = Netflix
4. 'SONY' = Sony
5. 'GOOGL' = Google


# Performance Metrics:
1. Mean Absolute Error (MAE): Measures the average magnitude of errors between actual and predicted prices.
2. Mean Squared Error (MSE): Measures the average squared difference between actual and predicted prices.
3. Root Mean Squared Error (RMSE): The square root of MSE, providing error magnitude in the same units as the output variable.
4. R-squared (R2) Score: A statistical measure indicating the proportion of variance explained by the model.

# Coding file names
fyp_GRU_amzn.ipynb -> Training and testing GRU model on Amazon Stock.

fyp_GRU_apple.ipynb -> Training and testing GRU model on Apple Stock.

fyp_GRU_google.ipynb -> Training and testing GRU model on Google Stock.

fyp_GRU_netflix.ipynb -> Training and testing GRU model on Netflix Stock.

fyp_GRU_sony.ipynb -> Training and testing GRU model on Sony Stock.

fyp_LSTM_amzn.ipynb -> Training and testing LSTM model on Amazon Stock.

fyp_LSTM_apple.ipynb -> Training and testing LSTM model on Apple Stock.

fyp_LSTM_google.ipynb -> Training and testing LSTM model on Google Stock.

fyp_LSTM_netflix.ipynb -> Training and testing LSTM model on Netflix Stock.

fyp_LSTM_sony.ipynb -> Training and testing LSTM model on Sony Stock.

fyp_transformer_amzn.ipynb -> Training and testing Transformer model on Amazon Stock.

fyp_transformer_apple.ipynb -> Training and testing Transformer model on Apple Stock.

fyp_transformer_google.ipynb -> Training and testing Transformer model on Google Stock.

fyp_transformer_netflix.ipynb -> Training and testing Transformer model on Netflix Stock.

fyp_transformer_sony.ipynb -> Training and testing Transformer model on Sony Stock.

# Dependencies:
This project requires the following dependencies:

1. Python 3.8+
2. Pandas
3. Numpy
4. TensorFlow
5. Matplotlib
6. Scikit-learn
7. yfinance
8. pandas-ta


Final Year Project 2024 for MSc Data Science with Advanced Research.

# Contact
For any questions or issues, please contact rajabilalnazir@gmail.com.

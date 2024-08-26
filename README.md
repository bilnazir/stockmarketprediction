# Data Science Innovations in Financial Market Predictions
This project implements three different models to predict five different stocks from yahoo finance like Apple, Google, Amazon, Sony and Netflix. This projects predicts closing stock prices using historical data and technical indicators. The model are trained on adjusted closing prices and various technical indicators to predict future stock movements.

Following machine learning models are used in this project:
1. LSTM
2. GRU
3. Transformers.

# Overview
This project focuses on predicting the adjacent closing prices of stocks for Apple (AAPL), Amazon (AMZN), Netflix (NFLX), Sony (SONY), and Google (GOOGL). It uses three different models—Transformers, LSTM, and GRU—allowing users to compare their performance. The models are trained on historical data from 2012 to 2022, utilizing technical indicators like RSI and EMA to improve predictions.

Tcikers to use the dataset from yahoo finance:
import yfinance 
tickers = ['AAPL', 'AMZN', 'NFLX', 'SONY', 'GOOGL']
Each of these tickers are used to download the dataset for the respective company.
1. 'AAPL' = Apple
2. 'AMZN' = Amazon
3. 'NFLX' = Netflix
4. 'SONY' = Sony
5. 'GOOGL' = Google

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

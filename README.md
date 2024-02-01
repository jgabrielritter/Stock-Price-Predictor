# Stock-Price-Predictor

Overview
This Python script utilizes machine learning, specifically a Random Forest Regressor, to predict stock prices based on historical data. The script fetches historical stock data using the Yahoo Finance API, preprocesses the data, and trains a model for predicting future stock prices.

Dependencies
pandas
numpy
matplotlib
scikit-learn
plotly
yfinance
Setup
Install the required dependencies using pip install -r requirements.txt.
Run the script by executing python stock_price_predictor.py in the terminal.
Enter the stock symbol (e.g., AAPL), start date, and end date when prompted.
Features
Fetches historical stock data using Yahoo Finance API.
Prepares data for machine learning, scaling features, and creating target variables.
Splits data into training and testing sets.
Builds and trains a Random Forest Regressor model.
Evaluates the model using Mean Absolute Error.
Generates an interactive plot with actual and predicted stock prices.
Usage
Input the stock symbol, start date, and end date when prompted.
View the Mean Absolute Error to assess model performance.
Interactively explore predicted vs. actual stock prices on an interactive plot.
Note
The script may display warnings if there are NaN values in the dataset, providing options to replace or handle them.
Ensure proper data input and valid date formats.

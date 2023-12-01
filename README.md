# Streamlit LSTM Application

This is a web application that utilizes Streamlit for the frontend and an LSTM model deployed in the backend. It uses the facebook's Prophet ML library to help predict the stock/index prices for next n days/months/years.The application allows users to see the stock price prediction for both long term and short term.

## Table of Contents





## Features

1. Automatically detects the user country and shows prediction for top 5 stocks
2. Ability for users to set days and months or even years for which they want to see the predicted prices.
3. Ability to view other stocks of other countries also
4. For long term predictions, a comparison of the model’s predicted price with the analyst’s target price
5. For short term predictions, a sentiment analysis of the stock news to enable visualization of its impact on stock price

## Getting Started
Included in Fin-tool are the following Python modules:

geo_location.py: Provides information specific to a certain country by determining the user's current location.

The stock's correlation with its parent index is shown by index_correlation.py.

main.py: Utilizes the other files to generate the application and contains all of the Streamlit configurations and page setup.

Contains the Prophet ML model for stock price prediction (plot_charts.py). includes two functions in Python, one for long-term forecasting and the other for short-term forecasting.

sentiment.py: Gathers stock news from Google News and estimates the stock's trend using the VADER sentiment analysis tool.

stock_recomendation.py: This script retrieves a stock's analyst price target from Yahoo Finance.


## Installation
1.pip install -r requirements.txt
2.Run streamlit run main.py and access the application on localhost:8501



# Stock_Price_Predector
This project builds a machine learning model to predict the next day's movement of the NIFTY 50 index using historical market data and technical indicators.

The model uses Random Forest classification to predict whether the market will go up or down the next day based on historical price trends and technical indicators.

## Project Overview

Financial markets are highly dynamic and difficult to predict. This project explores how machine learning techniques can be applied to historical stock market data to identify patterns and make predictions.

The model predicts:

1 → Market goes UP tomorrow  
0 → Market goes DOWN tomorrow  

The dataset used is the historical data of the NIFTY 50 index obtained from Yahoo Finance.

## Machine Learning Model

This project uses the Random Forest Classifier.

Random Forest is an ensemble machine learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

It works well for financial datasets because it can capture complex patterns in market behaviour.

## Features Used

The model uses the following predictors:

Market Data:
- Open price
- Close price
- High price
- Low price
- Volume

Technical Indicators:
- 20-day Moving Average (MA20)
- 50-day Moving Average (MA50)
- Relative Strength Index (RSI)

## Workflow

1. Download historical NIFTY 50 data using yfinance
2. Clean and preprocess the dataset
3. Create prediction targets
4. Generate technical indicators
5. Train a Random Forest model
6. Perform backtesting
7. Evaluate model performance

## Results

The model achieved a precision score between 0.53 and 0.57 during testing.

Financial markets are difficult to predict, so even small improvements over random guessing can be meaningful.

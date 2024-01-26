Financial Sentiment Analysis for Stock Price Prediction
Overview
This repository contains the code and datasets used in a study exploring the correlation between sentiment scores derived from financial text data, specifically tweets, and stock prices. The goal is to demonstrate how fluctuations in stock prices correspond with emotional scores from relevant financial texts over various time frames.

Purpose of the Study
The study aims to:

Establish a significant link between sentiment scores and stock price movements.
Examine the effectiveness of sentiment scores over different time intervals.
Explore the impact of sentiment scores on stock prices using various algorithms.
Validate the findings using different time scales and a set of validation metrics.
Scope and Usage
We utilized sentiment scores obtained by applying two methods:

RoBERTa: A transformer model for extracting sentiment scores.
VADER: A lexicon and rule-based sentiment analysis tool.
These methods were used to predict stock price changes, examining the effect of neutral and positive sentiment scores. The predictions were validated using metrics such as MSE, RMSE, R^2 scores, and correlation coefficients.

Applications
Computational Finance: To understand market sentiment and its impact on stock prices.
Quantitative Analysis: For developing models that can detect price movement signals based on sentiment analysis.
Dataset
The dataset comprises tweets related to financial markets and stock price data. It is sourced from Kaggle and is used to train machine learning models for both regression and classification tasks.

Validation Metrics
To ensure the accuracy of predictions, the following metrics were used:

Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R^2 Score
Pearson Correlation Coefficients and P-values
Models and Timeframes
The study tests various machine learning models across different time intervals to identify the most effective approach for price prediction.

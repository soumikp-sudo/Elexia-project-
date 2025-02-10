Stock Market Price Prediction with Sentiment Analysis
Overview
This project implements a comprehensive stock market prediction system that combines financial data analysis, machine learning, and sentiment analysis to forecast stock prices.
Features

Historical stock price data retrieval
Financial news sentiment analysis
Machine learning price prediction
Performance visualization and reporting

Prerequisites

Python 3.8+
Libraries:

yfinance
pandas
scikit-learn
textblob
matplotlib
seaborn
requests



Installation
bashCopypip install yfinance pandas scikit-learn textblob matplotlib seaborn requests
Configuration

Obtain a NewsAPI key from NewsAPI.org
Replace NEWS_API_KEY in the script with your key

Usage
pythonCopy# Example usage in main() function
predictor = StockMarketPredictor('AAPL', '2022-01-01', '2023-12-31', NEWS_API_KEY)
Components

Stock Data Retrieval: Fetches historical stock prices
Sentiment Analysis: Evaluates news article sentiment
Machine Learning Model: Random Forest Regression
Visualization: Price prediction charts

Model Metrics

Mean Squared Error (MSE)
R-squared (R2) Score

Visualization

Actual vs Predicted Price Chart
Sentiment Analysis Summary

Customization

Modify stock symbol
Adjust date range
Experiment with different ML models

Limitations

Prediction accuracy depends on market volatility
Sentiment analysis is based on textual analysis
Past performance doesn't guarantee future results

Contributing

Fork the repository
Create your feature branch
Commit changes
Push to the branch
Create a Pull Request

License
MIT License
Disclaimer
This project is for educational purposes. Do not use for actual financial trading decisions.

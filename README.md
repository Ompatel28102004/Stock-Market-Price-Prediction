# Stock Prediction with Sentiment Analysis

This project combines machine learning techniques to predict stock prices by incorporating sentiment analysis of tweets along with traditional stock prediction models.

## Project Overview
- **LSTM (Long Short-Term Memory)**: A deep learning model for predicting stock prices based on historical data.
- **ARIMA (AutoRegressive Integrated Moving Average)**: A statistical model for time series forecasting.
- **Linear Regression**: A classical machine learning method for stock price prediction.
- **Sentiment Analysis**: Analyzing tweets using NLP techniques to gauge market sentiment.

## Files
- `LSTM_final_Close.ipynb`: LSTM-based stock prediction model.
- `STOCK_ARIMA.ipynb`: ARIMA model for stock price prediction.
- `final_ml_linear.ipynb`: Linear regression model for stock price prediction.
- `sentiment_analysis_tweets.ipynb`: Sentiment analysis using tweets to influence stock predictions.

## Installation
To run the project, ensure you have the following Python packages installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow nltk yfinance tweepy
```

## Dataset
- Stock price data is fetched using the `yfinance` library.
- Twitter sentiment data is collected using `tweepy` API.

## Contributing
Feel free to fork this repository and contribute by submitting a pull request.

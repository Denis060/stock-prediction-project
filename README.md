# Stock Prediction Project

This project uses machine learning models to predict buy/sell signals for AAPL stock based on historical data and feature engineering.

## Project Overview

The project includes two classifiers:
- **Decision Tree Classifier**
- **K-Nearest Neighbors Classifier**

Both models were trained and evaluated to predict buy/sell signals based on the closing price and engineered features such as moving averages and volatility.

## Features and Data

The dataset includes:
- Closing prices, volume, daily returns, and 10-day and 50-day moving averages.
- Target variable: +1 for 'buy' if the next day's closing price is higher, -1 for 'sell' otherwise.

## Models

1. **Decision Tree Classifier**: Known for interpretability and efficient performance.
2. **K-Nearest Neighbors (KNN) Classifier**: Uses distance calculations to classify new data points.

## Results

Both models achieved high accuracy, but **Decision Tree** was preferred for its interpretability and ease of understanding.

## Usage

To replicate the project, follow these steps:
- Install required libraries: `yfinance`, `numpy`, `pandas`, `scikit-learn`.
- Download AAPL stock data and perform feature engineering.
- Train both models and compare their accuracy.

## License

This project is open-source and available under the [MIT License](LICENSE).

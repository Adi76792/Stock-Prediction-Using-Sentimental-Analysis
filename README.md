# Stock Prediction using Numerical & Sentiment Analysis Project

## Overview

This project is focused on predicting the stock prices of the Bombay Stock Exchange (BSE) by integrating sentiment analysis from news headlines. The prediction model is built using Long Short-Term Memory (LSTM) networks, with additional features extracted from news headlines using Natural Language Processing (NLP) techniques. The project demonstrates how financial data combined with sentiment data can be used to enhance stock price predictions.

## Features

- **Stock Price Data**: Historical stock prices for the BSE are retrieved using the `yfinance` API.
- **Sentiment Analysis**: Sentiment analysis is performed on news headlines using TextBlob and VaderSentiment.
- **LSTM Model**: An LSTM model is trained to predict future stock prices based on historical stock data.
- **Sentiment Integration**: The sentiment data is combined with the stock price data to improve the prediction accuracy.

## Requirements

To run this project, you need to install the following dependencies:

```bash
pip install numpy pandas matplotlib seaborn tensorflow plotly scikit-learn yfinance vaderSentiment textblob catboost
```

## Data

The project uses two main datasets:
1. **Stock Prices**: Historical stock prices for the BSE are downloaded using `yfinance`.
2. **News Headlines**: News headlines are processed to extract sentiment scores, which are then merged with the stock price data.

## Model Training

The LSTM model is trained on historical stock data, and then sentiment scores are integrated as additional features. The model's performance is evaluated using metrics like Mean Absolute Error (MAE) and Mean Squared Error (MSE).

## Visualization

The project includes visualizations of the stock price predictions, comparison of actual and predicted prices, and sentiment analysis results. These visualizations are generated using Matplotlib and Plotly.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- **Data Sources**: Thanks to `yfinance` for providing easy access to financial data.
- **Libraries**: Thanks to the developers of the Python libraries used in this project.

---

Feel free to customize this README to suit your project's needs.

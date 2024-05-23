# CMPE-258-Project
**Stock Market Prediction using Sentiment Analysis of Twitter Data**

This repository contains the code and documentation for a project aimed at predicting stock market movements using sentiment analysis of Twitter data. The project leverages advanced machine learning techniques to analyze social media sentiment and combine it with traditional stock market data for more accurate predictions.

### Project Overview
Stock markets play a crucial role in the global economy, and predicting their movements accurately can provide valuable insights for investors and businesses. Our project focuses on harnessing the power of social media, particularly Twitter, to gauge public sentiment about specific stocks. By analyzing tweets and correlating sentiment with stock prices, we aim to develop predictive models that enhance investment decision-making.

### Key Features
- Data Collection: We collect stock market data using the Yahoo Finance API and Twitter data using the SNScrape tool.
- Sentiment Analysis: We implement sentiment analysis using the twitter-XLM-roBERTa-base model to extract sentiment from Twitter data.
- Machine Learning Models: We implement three predictive models:
  - TabNet Regressor: A deep learning model specifically designed for tabular data.
  - Random Forest Regressor: An ensemble learning method that constructs multiple decision trees.
  - CNN-LSTM Based Neural Network: Integrates Convolutional Neural Networks (CNNs) with Long Short-Term Memory (LSTM) networks.
- Evaluation Metrics: We evaluate the models using Mean Absolute Error (MAE) and Mean Absolute Percentage Error (MAPE).

### Getting Started
To run the project locally, follow these steps:
1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Follow the instructions in the respective model directories to train and evaluate the models.

### Conclusion
Our project demonstrates the potential of integrating social media sentiment analysis with traditional stock market data for more accurate predictions. While the TabNet Regressor and Random Forest Regressor show varying degrees of success, the CNN-LSTM model emerges as the frontrunner with remarkably precise predictions. This work sets the stage for further advancements in financial forecasting using hybrid data sources.

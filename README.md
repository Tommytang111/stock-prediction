# NVDA Daily Price Movement Prediction
## Overview
Designed and implemented an end-to-end system that combines deep learning models and sentiment analysis techniques to predict stock price movements. The project integrated financial data from public sources with real-time news sentiment to improve prediction accuracy.
## Key Components & Techniques:
 - RNN & LSTM Networks: Developed recurrent neural network (RNN) and LSTM models to capture temporal trends in historical stock price data.
 - CNN-based Feature Extraction: Built a convolutional neural network (CNN) model to extract and process features from textual news data.
 - BERT Fine-Tuning: Fine-tuned a pre-trained BERT model for sentiment analysis on financial news headlines, labeling them as positive, negative, or neutral.
 - Sentiment Analysis & Aggregation: Created pipelines that generate and aggregate daily sentiment scores from diverse news sources.
 - Data Integration: Merged stock price data (retrieved using yfinance) with news sentiment metrics to perform a comparative analysis via dual-axis visualizations.
 - Evaluation: Compared the predictive power of deep learning models with the influence of daily news sentiment by visualizing correlations between news sentiment trends and daily stock price movements.
## Technologies & Libraries Used:
TensorFlow/Keras & Hugging Face Transformers: For building and fine-tuning deep learning models (RNN, LSTM, CNN, and BERT).
Pandas & NumPy: For data preprocessing and manipulation.
Matplotlib: For plotting and visualizing stock prices versus sentiment trends.
yfinance: For fetching historical stock price data.
Regular Expressions & Python Standard Library (sys, os): For data scripting and handling diverse data formats.
## Outcome:
Demonstrated that integrating advanced sentiment analysis with traditional time-series forecasting methods can improve the interpretability and accuracy of stock price predictions. The system provided actionable insights by correlating sentiment shifts with market behavior.

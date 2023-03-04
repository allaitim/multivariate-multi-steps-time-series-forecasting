# multivariate-multi-steps-time-series-forecasting

This repository presents implementations of some deep learning algorithms: LSTM model and autots for multi-steps multivariate time series forecasting. 

LSTM model is a modification of the traditional lstm model ; its parameters can be changed for better forecasting when applied to a different dataset.
Autots is a Python automatic machine learning library developed for automatic time series forecasting.

Requirements:

tensorflow

pandas

keras

sklearn

numpy

matplotlib

autots

In the models, the stock price data of Apple is used. It was downloaded from Yahoo Finance. 

Train_lstm -- training lstm model and forecasting for 20 days; fig.4 illustrates a good accuracy of results;
Train_autots -- training and forecasting for 20 days with the autots library;
functions -- is the lstm model and helper functions;
saveautots -- contain the forecasted data for 20 days by model from autots library.

To apply the model to a different dataset, use the train.py scripts;  n_stepsin and n_stepsout can be rewritten depending on the application.

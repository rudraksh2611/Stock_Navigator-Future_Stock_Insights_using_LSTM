# Stock_ForesightStock - Price Prediction using LSTM

This project aims to predict the future closing prices of INFOSYS stock using Long Short-Term Memory (LSTM) networks. Developed during my summer break, this project is a practical application of the machine learning concepts I am currently learning. As an investor in the stock market, my interest in stock price movements inspired me to create this small, sweet project.

## Table of Contents
- [Overview](#overview)
- [Project Workflow](#project-workflow)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Results](#results)

## Overview
Predicting stock prices is a challenging task due to the volatile and non-linear nature of the market. LSTM networks are well-suited for this task as they can capture temporal dependencies in time-series data. This project focuses on predicting the closing prices of INFOSYS stock. As someone who invests in the stock market, understanding and predicting stock price trends is both a personal and professional interest.

## Project Workflow
1. **Data Loading**: Load historical stock price data.
2. **Data Preprocessing**: Handle missing values, normalize the data, and visualize the original data.
3. **Feature Selection**: Select relevant features and scale them.
4. **Model Training**: Train the LSTM model on the training dataset.
5. **Evaluation**: Evaluate the model's performance and visualize predictions.
6. **Future Prediction**: Predict future stock prices and visualize the results.

## Data Preprocessing
- Load the historical stock price data.
- Handle missing values by dropping rows with null values.
- Normalize the data for better model performance.
- Visualize the original stock price data to understand its trend.

## Model Training
- Build and compile the LSTM model with appropriate layers.
- Train the model using the preprocessed data.
- Validate the model using a separate test dataset.
- Save the model architecture and weights for future use.

## Results
- Make predictions on the test dataset.
- Inverse transform the predicted data to its original scale.
- Visualize the predicted vs actual stock prices using graphs.
- Evaluate the model performance using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).

# Prediction Result:
![Prediction_Result](https://github.com/rudraksh2611/Stock_Prediction_Using-LSTM/assets/117443595/96d905b3-0967-4971-a035-65bd6f701150)




# Stock Navigator

## Table of Contents

1. [Overview](#overview)
2. [Key Features](#key-features)
3. [Project Components](#project-components)
4. [Data Preprocessing](#data-preprocessing)
5. [Feature Engineering and Analysis](#feature-engineering-and-analysis)
6. [Model Architecture](#model-architecture)
7. [Model Training](#model-training)
8. [Deployment](#deployment)
9. [Installation](#installation)
10. [Usage](#usage)
11. [Results](#results)

## Overview

**Stock Navigator** is an advanced stock market prediction system designed to forecast future stock prices with high accuracy. This system utilizes Long Short-Term Memory (LSTM) neural networks to anticipate future stock prices based on historical data. The project was developed to provide precise and reliable stock price predictions, aiding investors in making informed decisions.

## Key Features

- **LSTM Neural Networks:** Utilizes LSTM models for accurate time-series forecasting.
- **Comprehensive Data Processing:** Handles historical stock price data and various technical indicators.
- **Feature Engineering:** Includes feature selection and optimization to enhance model performance.
- **Real-Time Predictions:** Provides real-time stock price forecasts through a user-friendly interface.

## Project Components

1. **Data Collection:** Historical stock price data is collected from reliable sources.
2. **Data Preprocessing:** Data is cleaned and transformed for model training.
3. **Feature Engineering:** Technical indicators and other relevant features are computed.
4. **Model Training:** LSTM models are trained on the processed data.
5. **Model Evaluation:** Model performance is evaluated using various metrics.
6. **Prediction Interface:** A web interface (alternative to Flask) displays the stock price predictions.

## Data Preprocessing

- **Data Sources:** Stock price data sourced from [Data Source Name].
- **Data Cleaning:** Missing values and outliers are handled.
- **Feature Selection:** Features such as Moving Average, RSI, etc., are computed.

## Feature Engineering and Analysis

Through extensive analysis of various features, it was determined that `Volume` and `VWAP` did not contribute to the model's efficiency. As a result, these features were excluded from the final model to enhance performance. The final feature set includes:

- **Open Price**
- **Close Price**
- **High Price**
- **Low Price**
- **Moving Average**
- **Relative Strength Index (RSI)**
- **Other Technical Indicators**

## Model Architecture

- **LSTM Model:** The core of the prediction system. Designed to capture long-term dependencies and trends in stock price data.

## Model Training

- **Training Data:** Historical stock prices with selected features.
- **Validation Data:** Used to tune hyperparameters and avoid overfitting.
- **Evaluation Metrics:** Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared score.

## Deployment

The system can be deployed using various web technologies. An alternative to Flask can be utilized for displaying predictions:

- **Web Interface:** Integrates with the model to show real-time predictions.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/username/stock-navigator.git
    ```
2. Navigate to the project directory:
    ```bash
    cd stock-navigator
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Train the model:
    ```bash
    python train_model.py
    ```
2. Run the web interface:
    ```bash
    python app.py
    ```

## Results

Here is a sample result of the Stock Navigator's predictions:

### Prediction vs Actual Price

![Prediction_Result](https://github.com/rudraksh2611/Stock_Prediction_Using-LSTM/assets/117443595/96d905b3-0967-4971-a035-65bd6f701150)
*Figure 1: A comparison of predicted stock prices versus actual prices.*

For any queries or support, please contact [workrsb2611@gmail.com](mailto:your.email@example.com).

# Predicting Apple Stock Price Using LSTM with Keras Tuner

This repository contains a project for predicting Apple Inc.'s stock prices using a Long Short-Term Memory (LSTM) neural network. The model is optimized using **Keras Tuner**, a library for hyperparameter tuning in deep learning models. The dataset used for training and testing the model is sourced from Yahoo Finance.

---

## Overview

Stock price prediction is a challenging task due to the volatile and non-linear nature of financial markets. This project demonstrates the use of deep learning techniques, particularly LSTM, to model and predict the future stock prices of Apple Inc. LSTM networks are well-suited for time-series data, as they can capture long-term dependencies and trends.

---

## Features

1. **Data Collection**:
   - Stock price data for Apple Inc. is retrieved using the **Yahoo Finance API**.
   - The dataset includes daily closing prices over a specified time frame.

2. **Preprocessing**:
   - Data is normalized to improve model performance.
   - Splitting of data into training and testing sets.
   - Sequence generation to create time-series input for LSTM.

3. **Model Architecture**:
   - LSTM layers are used to process time-series data.
   - Dense layers are added for final predictions.

4. **Hyperparameter Tuning**:
   - **Keras Tuner** is used to optimize hyperparameters like:
     - Number of LSTM units.
     - Dropout rates.
     - Learning rate.
     - Number of dense units.

5. **Visualization**:
   - Historical stock prices and predictions are visualized for comparison.
   - Training and validation loss trends are plotted.

---

## Requirements
- TensorFlow
- Keras Tuner
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Yahoo Finance API (`yfinance` library)

---

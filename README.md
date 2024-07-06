# Energy Consumption Prediction using LSTM

This repository contains a project that predicts energy consumption using Long Short-Term Memory (LSTM) networks. The goal is to provide accurate forecasts of energy usage to help users optimize their energy consumption.

### Project Overview
Energy consumption prediction is crucial for managing and optimizing energy usage in households and industries. In this project, we utilize LSTM, a type of recurrent neural network (RNN), to predict future energy consumption based on historical data.

### Dataset
The Household Power Consumption Dataset from the UCI Machine Learning Repository is used. The dataset contains measurements of electric power consumption in a single household over four years.

### Preprocessing Steps
1. Loading and Cleaning Data: Handle missing values and convert data types.
2. Exploratory Data Analysis (EDA): Visualize data to understand patterns and distributions.
3. Feature Engineering: Create lag features and perform scaling.

### Model Building
#### LSTM Model
* Model Architecture:

1. Two LSTM layers with 50 units each.
2. Dropout and BatchNormalization layers for regularization.
3. Dense output layer with a single unit.
   
* Training:

1. Model trained on historical energy consumption data.
2. Evaluation using RMSE, MAE, MAPE, and R² metrics.

### Results
The LSTM model achieved the following performance metrics:

RMSE: 0.056
MAE: 0.029
MAPE: 18.69%
R²: 0.9968

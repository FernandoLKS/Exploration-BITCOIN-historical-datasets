# Bitcoin Price Analysis and Prediction
This repository contains an analysis and implementation of regression models to predict Bitcoin prices using historical data from 2018 to 2024. The aim is to explore various machine learning techniques and apply them to the Bitcoin dataset to develop predictive models.

# Dataset
The Bitcoin dataset used for this project is publicly available on Kaggle: (https://www.kaggle.com/datasets/novandraanugrah/bitcoin-historical-datasets-2018-2024)

Bitcoin Historical Datasets (2018-2024).
The dataset includes daily Bitcoin prices and various financial indicators over the specified time period, which will serve as the foundation for building and evaluating predictive models.

# Project Overview
In this project, I implemented four predictive models:
1. **Linear Regression** (using `scikit-learn`)
2. **Random Forest Regressor** (using `scikit-learn`)
3. **Linear Neural Network** (using `PyTorch`)
4. **Non-linear Neural Network** (using `PyTorch`)

## Models Implemented

### 1. Linear Regression (scikit-learn)
A simple linear regression model that assumes a linear relationship between the input features and the target variable (Bitcoin close prices).

### 2. Random Forest Regressor (scikit-learn)
An ensemble learning method that operates by constructing multiple decision trees and outputting the average prediction of the individual trees.

### 3. Linear Neural Network (PyTorch)
A neural network with a single linear layer. This model acts similarly to linear regression but is built using `PyTorch`, allowing for more flexibility and easier extension to more complex architectures.

### 4. Non-linear Neural Network (PyTorch)
A deeper neural network with multiple hidden layers and **ReLU** activations, allowing it to capture non-linear relationships in the data. This model was designed to provide a more robust prediction compared to the linear models.

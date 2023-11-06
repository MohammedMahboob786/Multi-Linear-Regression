# Fuel Consumption Prediction with Multiple Linear Regression

This repository contains a notebook for building a multiple linear regression model to predict fuel consumption based on various features. The model is developed using the scikit-learn and statsmodels libraries. 

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Data Preprocessing](#data-preprocessing)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Residual Analysis](#residual-analysis)
- [Making Predictions](#making-predictions)

## Introduction

The goal of this project is to develop a predictive model for fuel consumption using multiple linear regression. This model can be used to estimate fuel consumption based on various features like engine size, horsepower, and more.

## Data

The dataset used in this project is 'FuelConsumption.csv'. It contains information about various car models and their fuel consumption. The dataset is preprocessed to handle missing values, convert categorical features into numerical format, and perform feature scaling.

## Data Preprocessing

Data preprocessing steps include:
- Handling missing values
- Converting categorical features to numerical format using one-hot encoding
- Splitting the data into training and testing sets
- Scaling the numerical features using Min-Max scaling

## Model Building

The multiple linear regression model is built using scikit-learn's LinearRegression and statsmodels' OLS. Feature selection is performed through Recursive Feature Elimination (RFE) to select the most relevant features. The model's performance is analyzed using various statistics, including p-values and VIF.

## Model Evaluation

The model's performance is evaluated using the R-squared value (coefficient of determination). Visualizations are provided to understand the spread between the actual and predicted values.

## Residual Analysis

Residual analysis is conducted to check for any patterns or anomalies in the model's errors. Various plots are generated to visualize the relationship between features and residuals.

## Making Predictions

The trained model is used to make predictions on a test dataset. The predictions are compared to the actual values to assess the model's accuracy.

Feel free to explore the code and use it for your own fuel consumption predictions.

---

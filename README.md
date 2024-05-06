# Clustering_supply_chain
Clustering Supply Chain variables to improve prediction of freight pricing
# Data Preprocessing and Machine Learning Model Building

This repository contains scripts for data preprocessing and machine learning model building using a dataset from Google Drive. The scripts include data cleaning, feature engineering, and training several regression models to predict a target variable.

## Description

The dataset is initially loaded from a CSV file located in a Google Drive folder. The script performs various data preprocessing steps including renaming columns, converting data types, handling missing values, and feature engineering. The dataset is used to train regression models to predict a financial charge amount (`F_CHG_AMT`).

## Features

- **Data Cleaning**: Includes converting strings to numeric values, handling dates, and cleaning up column names.
- **Feature Engineering**: Creation of new features based on existing data, such as interaction terms and polynomial features.
- **Machine Learning Models**: Training of multiple regression models including Random Forest, Gradient Boosting, XGBoost, and Linear Regression.
- **Model Evaluation**: Evaluation of model performance using RMSE (Root Mean Square Error).
- **Visualization**: Includes plots of distributions and a correlation matrix using Seaborn and Matplotlib.

## Installation

1. Clone this repository to your local machine or Google Colab environment.
2. Ensure you have Python installed, along with the following packages:
   - `pandas`
   - `numpy`
   - `matplotlib`
   - `seaborn`
   - `sklearn`
   - `xgboost`

## Usage

To run the scripts, you will need to mount your Google Drive if using Google Colab:

```python
from google.colab import drive
drive.mount('/content/drive')

## Models Included
Random Forest Regressor
Gradient Boosting Regressor
XGBoost Regressor
Linear Regression
Each model is evaluated using a train-test split and the RMSE metric to determine the model's effectiveness.


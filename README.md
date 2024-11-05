# Sales Forecasting Project

## Overview

This project involves building a predictive model to forecast sales based on historical data. The dataset used includes various features such as date, store, and sales figures, allowing for a detailed analysis of sales trends over time.

## Contents

- `train.csv`: The dataset used for training the models.
- `sales_forecasting.py`: The main Python script that contains the code for data preprocessing, exploratory data analysis (EDA), and model training.

## Features

- **Data Preprocessing**: 
  - Extracts year, month, and day from the date.
  - Identifies holidays using the `holidays` library.
  - Creates cyclic features for month and day to capture seasonality.
  - Determines whether a day is a weekend.

- **Exploratory Data Analysis**:
  - Visualizes average sales based on different features.
  - Plots sales trends over days.
  - Calculates and visualizes the Simple Moving Average (SMA) for a specified window.

- **Statistical Analysis**:
  - Displays distributions and box plots of sales data.
  - Generates a heatmap for correlation analysis of features.

- **Model Training**:
  - Trains multiple regression models including:
    - Linear Regression
    - Lasso Regression
    - Ridge Regression
    - XGBoost Regressor
  - Evaluates models using Mean Absolute Error (MAE) on both training and validation sets.

## Requirements

To run this project, you need to have the following packages installed:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`
- `holidays`

You can install the required packages using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost holidays
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sales_forecasting.git
   cd sales_forecasting
   ```

2. Place the `train.csv` file in the same directory as the script.

3. Run the script:
   ```bash
   python sales_forecasting.py
   ```

## Results

The output will include training and validation errors for each model, along with various visualizations to help understand sales trends and patterns.

## Reference

Geeks for Geeks.


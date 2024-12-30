# Gold Price Prediction Model

This repository contains the implementation of a predictive model for gold prices based on various economic factors. The project uses the **Random Forest Regressor** algorithm to analyze and predict future gold prices.

## Project Overview

Gold has long been used as a hedge against inflation and economic uncertainty. The aim of this project is to develop a model capable of predicting gold prices using historical data and additional economic indicators such as stock indices and currency exchange rates. The **Random Forest Regressor** is used for its ability to handle complex relationships between variables and provide accurate predictions.

## Features

- Historical data processing (2008–2018).
- Data visualization and correlation analysis.
- Predictive modeling using **Random Forest Regressor**.
- Model evaluation metrics (R² score and Mean Squared Error).
- Comparison of predicted vs actual gold prices using scatter and time-series plots.

## Technologies Used

The implementation leverages the following technologies:

- **Python** (Jupyter Notebook)
- **pandas** and **numpy** for data manipulation and processing.
- **matplotlib** and **seaborn** for data visualization.
- **scikit-learn** for predictive modeling and evaluation.

## Dataset

The data was sourced from [Kaggle's Gold Price Data](https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data). Key features of the dataset:
- `Date`: Daily timestamps.
- `SPX`: S&P 500 index values.
- `GLD`: Gold prices (target variable).
- `USO`: Crude oil prices.
- `SLV`: Silver prices.
- `EUR/USD`: EUR/USD exchange rates.

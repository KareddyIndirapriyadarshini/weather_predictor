# Temperature Prediction Project

## Overview
This project predicts the next day's average temperature in a place using historical weather data from 2014 to 2024. The project uses machine learning models (Ridge Regression and Random Forest) implemented in a Jupyter notebook (`weather_pred.ipynb`). It includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and visualizations to provide insights into temperature patterns and model performance.

## Dataset
- **File**: `weather_data.csv`
- **Source**: Historical weather data for Bengaluru (2014–2024)
- **Features**: Temperature, Minimum/Maximum Temperature, Dew Point, Relative Humidity, Sea Level Pressure, Visibility, Cloud Cover, etc.
- **Target**: Next day's average temperature

## Requirements
- Python 3.12.7 (or compatible)
- Libraries:
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn

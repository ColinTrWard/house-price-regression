# House Price Regression

A machine learning project that predicts house sale prices using the Ames Housing dataset. 
Built to demonstrate regression techniques, feature engineering, and gradient boosting with XGBoost.

## Overview

Using 74 features describing nearly every aspect of residential homes in Ames, Iowa, this project 
trains an XGBoost regression model to predict sale prices. The model achieves an R² score of 0.92, 
meaning it explains 92% of the variation in house prices.

## Tech Stack

- Python 3
- XGBoost
- scikit-learn
- pandas
- numpy
- matplotlib
- Jupyter Notebook

## Key Concepts Covered

- Handling missing data at scale
- Label encoding categorical features
- Gradient boosting with XGBoost
- Regression metrics (MAE, RMSE, R²)
- Feature importance visualization

## Results

| Metric | Score |
|--------|-------|
| Mean Absolute Error | $16,094 |
| Root Mean Squared Error | $24,635 |
| R² Score | 0.9209 |

## Key Findings

- **Overall quality** rating was by far the strongest predictor of sale price
- **Garage size, central air, and living area** were the next most important features
- The model performs best on mid-range homes and shows more variance on high-value outliers

## How to Run

1. Clone the repo
2. Download `train.csv` from [Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
3. Place `train.csv` in the project folder
4. Install dependencies: `conda install xgboost scikit-learn pandas numpy matplotlib`
5. Open `house-price-regression.ipynb` in Jupyter
6. Run all cells top to bottom

## Dataset

Ames Housing dataset sourced from the Kaggle House Prices competition.

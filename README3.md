# 2nd Task: Apple Stock Price Prediction

## Task Objective

The objective of this notebook ([2ndTask.ipynb](2ndTask.ipynb)) is to analyze Apple Inc. (AAPL) stock data and build a simple linear regression model to predict the closing price based on other stock features. The notebook also explores the impact of including trading volume as a feature.

## Dataset Used

- **Apple Stock Data**: Downloaded using the `yfinance` library for the period from January 1, 2023, to January 1, 2025.
- Features include:
  - Open price
  - High price
  - Low price
  - Close price (target)
  - Volume

## Models Applied

- **Linear Regression**: 
  - Built using `scikit-learn`'s `LinearRegression`.
  - Two models were trained:
    1. Using 'Open', 'High', and 'Low' as features.
    2. Adding 'Volume' as an additional feature.
  - Data was split into training and testing sets using `train_test_split`.

## Key Results and Findings

- **Exploratory Analysis**: Scatter plots were used to visualize relationships between features and the closing price.
- **Model Performance**:
  - The linear regression model achieved a high score (R²) when predicting the closing price using 'Open', 'High', and 'Low'.
  - Including 'Volume' as a feature did not significantly improve the model's performance, indicating that volume has little linear relationship with the closing price in this context.
- **Visualization**: A scatter plot of actual vs. predicted closing prices showed that the model predictions closely follow the actual values, confirming the effectiveness of the linear regression approach for this

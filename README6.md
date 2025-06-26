# 6th Task: House Price Prediction

## Task Objective

The objective of this notebook ([6thTask.ipynb](6thTask.ipynb)) is to build and evaluate regression models for predicting house prices based on features such as area, number of bedrooms, and location. The notebook compares the performance of linear regression and gradient boosting regression models.

## Dataset Used

- **House Price Prediction Dataset**: Loaded from `House Price Prediction Dataset.csv`.
- Features include:
  - Area
  - Bedrooms
  - Location (one-hot encoded)
  - Price (target variable)

## Models Applied

- **Linear Regression**:
  - Implemented using `scikit-learn`'s `LinearRegression`.
- **Gradient Boosting Regressor**:
  - Implemented using `scikit-learn`'s `GradientBoostingRegressor`.
- **Preprocessing**:
  - Missing values handled by dropping rows or filling with median/mean.
  - Location feature one-hot encoded.
  - Features scaled using `StandardScaler`.
  - Data split into training and testing sets.

## Key Results and Findings

- **Model Evaluation**:
  - Both models were evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
  - Gradient Boosting Regressor generally provided better predictive performance than Linear Regression.
- **Visualization**:
  - A scatter plot compared actual vs. predicted prices for the Gradient Boosting model, showing good alignment along the ideal prediction line.
- **Conclusion**:
  - Feature engineering and advanced regression models like Gradient Boosting can significantly improve house price prediction accuracy.

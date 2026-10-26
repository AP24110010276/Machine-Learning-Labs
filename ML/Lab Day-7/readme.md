# Machine Learning Labs: Regression

## Overview
This section contains three Python notebooks demonstrating Simple Linear Regression, Multiple Linear Regression, and Polynomial Regression using a house price prediction example.

## Experiments

### 1. Simple Linear Regression
**Notebook:** `Linear_Regression_AP24110010276.ipynb`

- Creates a sample dataset containing house area and price.
- Trains a Linear Regression model using scikit-learn.
- Displays the slope and intercept.
- Predicts prices for existing data and a new house.
- Visualizes actual prices and the regression line.

### 2. Multiple Linear Regression
**Notebook:** `MULTIPLE_LINEAR_REGRESSION_AP24110010276.ipynb`

- Uses house area, number of rooms, age, and distance as input features.
- Predicts house prices using multiple independent variables.
- Displays model coefficients and intercept.
- Predicts the price of a new house.
- Calculates the R-squared score.

### 3. Polynomial Regression
**Notebook:** `Polynomial_Regression_AP24110010276.ipynb`

- Converts the area feature into polynomial features of degree 2.
- Trains a Linear Regression model on the transformed features.
- Displays coefficients and intercept.
- Predicts house prices for existing data and a new house.
- Visualizes the polynomial curve and calculates the R-squared score.

## Dataset
All three notebooks create their own small sample house price dataset directly in Python. No external dataset file is required.

## Libraries Used
- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## How to Run
1. Open a notebook in Google Colab or Jupyter Notebook.
2. Run the cells in order.
3. Review the model coefficients, predictions, plots, and evaluation results.

## Learning Outcomes
- Understand the difference between simple, multiple, and polynomial regression.
- Train regression models using scikit-learn.
- Predict house prices using input features.
- Visualize regression results.
- Interpret the R-squared score where calculated.

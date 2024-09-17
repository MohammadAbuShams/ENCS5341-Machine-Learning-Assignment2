# Model Selection and Hyper-parameters Tuning

## Overview

This repository contains code for analyzing and modeling datasets using polynomial and logistic regression. The goal is to explore data, apply polynomial regression, ridge regression, and logistic regression, and analyze the performance of different models.

## Objectives

1. **Data Preparation:**
   - Read and split the dataset into training, validation, and testing sets.
   - Visualize the datasets using 3D scatter plots.

2. **Polynomial Regression:**
   - Implement polynomial regression with degrees ranging from 1 to 10.
   - Identify the best polynomial degree by evaluating validation error.
   - Plot the polynomial surfaces along with training data.

3. **Ridge Regression:**
   - Apply ridge regression on a polynomial of degree 8.
   - Determine the best regularization parameter by evaluating MSE on the validation set.

4. **Logistic Regression:**
   - Implement logistic regression with linear and quadratic decision boundaries.
   - Evaluate and compare training and testing accuracies.

## Dataset

- **data_reg.csv:** Contains 200 examples with features `x1`, `x2`, and target label `y`.
- **train_cls.csv:** Training data for binary classification with features `x1`, `x2`, and class label.
- **test_cls.csv:** Testing data for binary classification with features `x1`, `x2`, and class label.

## Prerequisites

- Python 3.
- Jupyter Notebook.
- Required Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `scikit-learn`

## Implementation

### 1. Data Preparation

- Load data from CSV files.
- Split into training, validation, and testing sets.
- Visualize data in a 3D scatter plot.

### 2. Polynomial Regression

- Apply polynomial regression with varying degrees (1 to 10).
- Plot validation error vs polynomial degree to determine the best degree.
- Visualize the polynomial surfaces.

### 3. Ridge Regression

- Apply ridge regression on an 8th-degree polynomial.
- Evaluate different regularization parameters to find the best MSE.

### 4. Logistic Regression

- Implement logistic regression with linear and quadratic decision boundaries.
- Compare accuracies on training and testing sets.
- Discuss overfitting and underfitting based on the model performance.

## Results

- **Polynomial Regression:** Degree 2 showed the best performance with the lowest validation error.
- **Ridge Regression:** A regularization parameter of 0.01 yielded the lowest MSE.
- **Logistic Regression:** The quadratic decision boundary model performed significantly better in terms of accuracy compared to the linear model.



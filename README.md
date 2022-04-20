# Regression Models Baseline
This repository contains code for evaluating various regression models from scikit-learn on a dataset. The code performs data preprocessing, model training, and model evaluation using several regression algorithms. The models included in this repository are:

Linear Regression
Polynomial Regression
Ridge Regression
Lasso Regression
Decision Tree Regressor
Random Forest Regressor
Extra Trees Regressor
MLP Regressor

# Getting Started

## Prerequisites
Make sure you have the following libraries installed:

NumPy
Pandas
Matplotlib
Scikit-learn
Seaborn

## Usage
You can run the code by executing the script. The script performs the following steps:

Import the required libraries.
Load the development and evaluation datasets.
Perform data preprocessing, including handling outliers and feature selection.
Split the development dataset into training and testing sets.
Scale and encode the columns.
Train and evaluate the regression models.
Select the best performing models based on evaluation metrics.
Use the best models to make predictions on the evaluation dataset.
Visualize the results using scatter plots and heatmaps.

## Results
The code outputs the root mean squared error (RMSE) and R-squared scores for each model on both the training and testing sets. It also generates scatter plots and heatmaps to visualize the predicted prices on the development and evaluation datasets.
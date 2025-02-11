# Car-Price-Prediction-Project-with-Machine-Learning



## Overview

This project aims to predict car prices using various regression models. A dataset containing car attributes has been used, and multiple regression techniques have been implemented to analyze the factors influencing car prices.

## Dataset

The dataset consists of various car features such as:

car_ID

symboling

CarName

fueltype

aspiration

doornumber

carbody

drivewheel

enginelocation

wheelbase

carlength

carwidth

carheight

curbweight

enginetype

cylindernumber

enginesize

fuelsystem

boreratio

stroke

compressionratio

horsepower

peakrpm

citympg

highwaympg

price

These features have been preprocessed and analyzed to ensure data quality before applying machine learning models.

## Models Implemented

The following regression models were implemented:

### Linear Regression: A simple yet powerful model that assumes a linear relationship between the independent variables and the target variable (car price).

### Decision Tree Regressor: A tree-based model that splits data into branches to make predictions based on conditions at each node.

### Random Forest Regressor: An ensemble learning method that builds multiple decision trees and averages their predictions for improved accuracy and reduced overfitting.

### Gradient Boosting Regressor: A boosting algorithm that sequentially builds trees, correcting errors from previous trees to improve predictive performance.

### Support Vector Regressor (SVR): A regression technique that uses support vector machines to find a hyperplane that best fits the data while minimizing prediction errors.

## Steps Followed

### Data Loading & Preprocessing: Handled missing values, encoded categorical variables, and scaled numerical data.

### Model Implementation: Trained five different regression models.

### Evaluation Metrics: Compared models based on Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-Squared (R²) score.

### Feature Importance Analysis: Identified key factors affecting car prices.

### Hyperparameter Tuning: Used GridSearchCV to optimize Random Forest hyperparameters.

## Results

The models were evaluated, and the best-performing model was selected based on R² score.

Feature importance analysis was performed to understand which variables contribute most to car pricing.

Hyperparameter tuning improved model accuracy.

# py_creditCard
# Credit card Spending Prediction

## Problem Statement

Predict the average spend of customers for the next 3 months in a regression problem.

## Overview

The task involves predicting customer spending for the next 3 months based on advertisement details. The dataset includes training and testing data, with features outlined in the data dictionary.

## Key Steps

1. **Import Libraries:**
   - Import necessary libraries for data analysis and model building.

2. **Load Data:**
   - Load training and testing data along with the data dictionary.

3. **Data Exploration and Preprocessing:**
   - Treat NULL values and handle outliers.
   - Explore gender distribution and perform basic data analysis.

4. **Feature Engineering:**
   - Log-transform right-skewed columns.
   - Check and address collinearity issues.

5. **Data Preprocessing:**
   - Label encode categorical variables and standardize numerical features.

6. **Train-Test Split:**
   - Split the data into training and validation sets.

7. **Model Building:**
   - Utilize Linear Regression, Random Forest, and CatBoost models for prediction.

8. **Model Evaluation:**
   - Assess model performance using RMSLE scores.

9. **Making Predictions:**
   - Use trained models to predict customer spending on the test data.

# Abalone-s-age-prediction


## Project Overview

This project focuses on predicting the age of abalone using physical measurements and machine learning.

The target variable, Age, is estimated from features such as length, diameter, height, whole weight, shucked weight, viscera weight, and shell weight.

## Dataset

The dataset contains physical measurements of abalone.

### Features
- Sex
- Length
- Diameter
- Height
- Whole Weight
- Shucked Weight
- Viscera Weight
- Shell Weight

### Target
- Age

## Data Preprocessing

The following preprocessing steps were performed:
- Checked for missing values
- Checked for duplicated rows
- Explored potential outliers
- Encoded the categorical `Sex` feature
- Scaled numerical features
- Split the data into training and testing sets

## Exploratory Data Analysis

Exploratory data analysis was performed to understand:
- Feature distributions
- Relationships between features
- Correlations between numerical variables
- Potential outliers

## Machine Learning Model

- We applied many models to evaluate each model and compare what is the best model.

## Model Evaluation

The model was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score



## Project Structure

```text
Abalone-Age-Prediction/
│
├── abalone_age_prediction.ipynb
├── abalone.data
└── README.md

# Residential Property Price Predictor

## Overview
This project implements supervised machine learning models to predict residential property prices based on key fundamental housing attributes. The objective is to automate and standardize property valuation using predictive modeling techniques.

## Dataset
The dataset utilized is the standardized housing price prediction dataset by Harish Kumar. It contains data on housing prices along with various property features such as total square footage, number of bedrooms, bathrooms, and categorical amenities like air conditioning and furnishing status.

## Methodology
The analytical pipeline consists of the following phases:
1. Data Preprocessing: Applying Label Encoding and One-Hot Encoding to categorical variables to convert them into numerical formats.
2. Exploratory Data Analysis: Generating correlation matrices and feature distribution plots to identify attributes with the highest impact on target pricing.
3. Feature Scaling: Applying Min-Max scaling to continuous variables to prevent magnitude bias during linear model training.
4. Model Training: Fitting a Baseline Multiple Linear Regression model and an Intermediate Decision Tree Regressor using an 80/20 train-test split.
5. Evaluation: Assessing model performance via Mean Absolute Error (MAE) and R-Squared metrics, and tuning the Decision Tree max depth to prevent overfitting.

## Key Findings
Analysis of the Decision Tree Feature Importance indicates that total square footage (area), the presence of air conditioning, and the number of bathrooms are the most heavily weighted factors driving real estate valuation within this dataset.

# Car Price Prediction using Machine Learning

## Project Overview

This project predicts car prices using machine learning regression models.

The dataset contains information about cars including brand, manufacturing year, engine size, fuel type, transmission, mileage, condition, and model.

This project was completed as part of the CodeAlpha Data Science Internship.

## Objective

The objective is to build a machine learning model that predicts car prices based on available car features.

## Dataset

The dataset contains 2,500 car records and 10 original columns.

The target variable is:

- Price

Features include:

- Brand
- Year
- Engine Size
- Fuel Type
- Transmission
- Mileage
- Condition
- Model

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Project Workflow

1. Dataset loading
2. Data exploration
3. Data quality checking
4. Exploratory data analysis
5. Feature engineering
6. Categorical feature encoding
7. Train-test split
8. Regression model training
9. Price prediction
10. Model evaluation
11. Model comparison
12. Visualization of actual and predicted prices

## Feature Engineering

A `Car_Age` feature was created from the manufacturing year.

## Machine Learning Models

The following regression models were evaluated:

- Linear Regression
- Random Forest Regression

## Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Project Structure

```text
CodeAlpha_Car_Price_Prediction/
│
├── dataset/
│   └── car_price.csv
│
├── car_price_prediction.ipynb
├── README.md
└── requirements.txt
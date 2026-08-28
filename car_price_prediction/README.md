# Car Price Prediction

## Overview

This project focuses on predicting the selling price of used cars using Machine Learning techniques.

The dataset contains information about used cars, including their present price, kilometers driven, manufacturing year, fuel type, seller type, and transmission.

## Dataset

The dataset contains 301 observations and 9 initial features.

The target variable is:

- `Selling_Price`

Some of the main features include:

- `Present_Price`
- `Kms_Driven`
- `Year`
- `Fuel_Type`
- `Seller_Type`
- `Transmission`

A new feature called `Car_Age` was also created during data preprocessing.

## Data Analysis and Preprocessing

The project includes:

- Exploratory data analysis
- Descriptive statistical analysis
- Checking missing values
- Numerical and categorical feature analysis
- Data visualization
- Feature engineering

## Machine Learning

Linear Regression was used to predict car selling prices.

The model was evaluated using:

- MAE
- MSE
- RMSE
- R²

Cross-validation was also performed to evaluate the model.

## Prediction

The trained model was used to predict the selling price of new car information.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Files

- `Car_data.ipynb` — Jupyter Notebook containing the analysis, preprocessing, modeling, and evaluation.
- `cardata.csv` — Dataset used in the project.


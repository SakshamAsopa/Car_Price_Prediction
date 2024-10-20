## Car_Price_Prediction
# Overview
This project aims to develop a robust car price prediction model using various regression techniques, including Linear Regression, Lasso Regression, Ridge Regression, and Elastic Net Regression. By leveraging historical data on used cars, the model predicts prices based on key features such as make, model, year, mileage, and condition.
# Features
Predict car prices based on multiple input features.
Compare the performance of different regression models.
Visualize the impact of each feature on predicted prices.
User-friendly interface for real-time predictions.
# Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Jupyter Notebook

The dataset used in this project is sourced from https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho?select=car+data.csv. It includes information about used cars, including:
Car_Name
Year
Selling_Price
Present_Price
Kms_Driven
Fuel_Type
Seller_Type
Transmission
Owner

# Data Preprocessing
Handled missing values
Encoded categorical variables
Normalized numerical features

# Models Implemented
## Linear Regression
Basic linear regression to establish a baseline.

## Lasso Regression
Implemented L1 regularization to reduce overfitting and improve model simplicity.

## Ridge Regression
Used L2 regularization to manage multicollinearity and improve prediction accuracy.

## Elastic Net Regression
Combined L1 and L2 regularization for optimal performance on complex datasets.

# Results
The models were evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² score. A comparative analysis of model performance is included in the Jupyter Notebook.

# Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

# House-Price-Prediction-
House Price Prediction


🏠 Overview 

The House Price Prediction project is a Machine Learning-based regression system designed to estimate the selling price of houses using various real-estate features.
By analyzing attributes like the number of bedrooms, bathrooms, total living area, condition, and proximity to amenities, the model learns complex patterns in the housing data to predict realistic property values.

This project demonstrates the end-to-end machine learning pipeline, including:

Data collection & preprocessing

Feature selection and engineering

Model training using RandomForestRegressor

Model evaluation and optimization

Deployment via a Streamlit web application


The dataset (House Price India.csv) contains 14,619 records and 23 attributes, offering insights into how different property characteristics impact house prices.

____________________________________________________________________________________________________________
⚙️ What This Project Does

🧮 Predicts house prices based on user input

📊 Learns from real estate data using supervised learning

🖥️ Provides an easy-to-use web app interface

📈 Helps visualize the impact of property features on price
____________________________________________________________________________________________________________
⚙️ Model Training

Model used: RandomForestRegressor from scikit-learn

Steps followed:

Data Cleaning – Handled missing values and unnecessary columns

Feature Selection – Selected most relevant predictors

Data Splitting – 80% training and 20% testing

Model Training – RandomForestRegressor tuned for optimal depth and estimators

Evaluation Metrics:

Mean Squared Error (MSE): 62,103,244,878.01

Root Mean Squared Error (RMSE): 149,205.23

R² Score: 0.71

This means the model explains ~58% of the variance in house prices — a good baseline for further tuning.

___________________________________________________________________________________________________________

💻 Streamlit Web App

File: app.py

Features:

Simple UI for entering house details

Real-time price prediction using trained model

Balloon animation and success messages

Error handling for invalid input or model load failures

Example Input:
Field	Example
Bedrooms	3
Bathrooms	2
Living Area	2100
Condition	4
Number of Schools Nearby	2

Predicted Price Output:

💰 Estimated House Price: $825,000.00

____________________________________________________________________________________________________________
🎯 Goal

To create a data-driven price estimation tool that helps buyers, sellers, and real estate analysts make more informed decisions.



__________________________________________________________________________________________________________

🧠 Tools and Technologies

Python 3.10+

pandas, numpy — data processing

scikit-learn — model building

Streamlit — web interface

joblib — model serialization




# Housing-Price-Prediction
Task Objective
The objective of this project is to predict housing prices based on key features such as area, number of bedrooms, and bathrooms using a Linear Regression model. The workflow includes data preprocessing, model training, evaluation, and result visualization.

Dataset Used
Source: Local CSV file (Housing.csv)

Path: C:/Users/MEGA/OneDrive/Desktop/py/Dataset/Housing.csv

Features:

area

bedrooms

bathrooms

Target:

price

Missing values in the dataset are handled by dropping incomplete rows. Feature values are standardized using StandardScaler.

Model Applied
Algorithm: Linear Regression

Library: scikit-learn

Steps:

Load and preprocess the dataset

Split data into training and testing sets

Train a Linear Regression model

Predict house prices on the test set

Evaluate the model using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

Key Results and Findings
The model performs reasonably well using only a few numerical features.

Evaluation metrics such as MAE and RMSE provide insight into prediction accuracy.

A scatter plot is used to visualize actual vs predicted prices, with separate colors for clarity.

# Machine-Learning-For-Beginners
A beginners guide to understand the basic concept of Machine Learning
# Predicting Weight Using Linear Regression
## Overview
This project uses Linear Regression to predict a person's weight based on their age and height.
## Steps Involved
### 1. Load the Data
We create a dataset with three columns:
Age
Height
Weight (the target variable)
### 2. Normalize the Data
We use Min-Max Scaling to scale Age and Height between 0 and 1. This helps improve model performance.
### 3. Train the Model
The data is split into training (80%) and testing (20%) sets.
The model is trained to predict Weight using Age and Height.
### 4. Make Predictions
The model predicts weight for the test data.
The predicted values are compared with the actual values.
### 5. Evaluate the Model
We use Mean Squared Error (MSE) to measure prediction accuracy. A lower MSE indicates better performance.
### 6. Results:
The model makes accurate predictions with minimal error.
Example Prediction:
Actual Weight: 95 kg
Predicted Weight: 95.0 kg

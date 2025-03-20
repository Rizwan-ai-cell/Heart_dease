Heart Disease Prediction

Overview

This project implements a heart disease prediction model using Random Forest Classifier. The dataset consists of patient medical records, and the goal is to predict whether a patient has heart disease based on various health indicators.

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Dataset

The dataset includes multiple features related to heart health, such as:

Age, Sex

Chest Pain Type

Resting Blood Pressure

Cholesterol Levels

Resting ECG Results

Maximum Heart Rate Achieved

Exercise-Induced Angina

ST Depression, ST Slope

Number of Major Vessels Colored by Fluoroscopy

Thalassemia Type

Target Variable: HeartDisease (0 = No, 1 = Yes)

Model Workflow

Data Preprocessing

Handling missing values and duplicates

Encoding categorical features

Splitting the dataset into training and testing sets

Model Training

Using Random Forest Classifier

Evaluation

Accuracy score

Confusion matrix

Classification report

How to Run

Install dependencies:

Run the script:

Results

The model achieves high accuracy in predicting heart disease.

A confusion matrix and classification report provide insights into performance.

Future Improvements

Experiment with different ML models (SVM, Neural Networks, etc.)

Apply feature engineering to improve performance.

Perform hyperparameter tuning for better accuracy.

# Task-for-ML-labs
Healthcare Appointment No-Show Prediction Task

This project focuses on predicting healthcare appointment no-shows using machine learning. The primary objectives are to understand patient behavior, optimize resource allocation, and improve scheduling efficiency at healthcare facilities.

### Overview
Dataset:\
Contains patient appointment records with features such as patient demographics, appointment details, health conditions, and historical attendance data.

Data Preprocessing:

Cleaning and exploring the dataset.\
Handling missing values, duplicates, and converting date/time columns.\
Encoding categorical variables and creating derived features (e.g., computed waiting time).\
Model Development:

Splitting the data into training and testing sets.\
Training classification models including Logistic Regression and Random Forest.\
Addressing class imbalance and tuning hyperparameters via GridSearchCV.\
Evaluating models using accuracy, precision, recall, F1-score, and ROC-AUC.\
Analysis and Interpretation:

Feature importance analysis reveals key predictors such as previous no-shows, SMS reminders, and waiting time.\
Comparative analysis of models guides actionable recommendations for reducing appointment no-shows.

Results\
Logistic Regression:

Accuracy: 80.6%\
ROC-AUC: 88.9%\
Higher recall for identifying no-shows.

Tuned Random Forest:

Accuracy: 82.0%\
ROC-AUC: 88.3%\
Slightly higher precision and comparable F1-score.

Usage\
Notebook:
Refer to Task from ML Labs.ipynb for detailed code, analysis, and visualizations.\
Requirements:
Install necessary packages using requirements.txt.\
Conclusion\
This repository provides a robust framework for predicting patient no-shows. The insights derived can help healthcare providers optimize appointment scheduling and improve patient engagement.

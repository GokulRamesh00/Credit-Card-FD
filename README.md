## Credit Card Fraud Detection with Machine Learning

## Overview

This project focuses on building a Credit Card Fraud Detection System using unsupervised anomaly detection and supervised classification models to identify fraudulent transactions effectively.

## Key Features

Anomaly Detection: Utilized Isolation Forest to detect anomalies, identifying 1% fraudulent transactions with 99% accuracy.

Data Preprocessing: Standardized features using StandardScaler and handled missing values with median imputation to ensure data consistency.

Model Implementation: Developed and tuned Naive Bayes, Decision Tree, Random Forest, Gradient Boosting, and XGBoost using GridSearchCV for hyperparameter optimization, achieving a 20% performance boost.

Model Evaluation: Assessed performance with metrics such as Precision, Recall, F1-Score, and Confusion Matrix, achieving 75% F1-Score and 74% Recall with XGBoost.

Feature Importance Visualization: Visualized key predictors to enhance interpretability and support data-driven decisions.

## Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, XGBoost

Techniques: Anomaly Detection, Feature Engineering, Hyperparameter Tuning, Model Evaluation

## File Structure

CreditCard.ipynb: Jupyter Notebook containing the full implementation of data preprocessing, anomaly detection, model training, and evaluation.

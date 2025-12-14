# machine-learning-model-comparison
Comparison of supervised machine learning models for classification and regression tasks using Python and scikit-learn.

# Machine Learning Model Comparison

## Overview
This project compares the performance of several supervised machine learning models
on both classification and regression tasks.
Models evaluated include Logistic Regression, Linear Regression, CART, K-Nearest Neighbors, Support Vector Machine, and Random Forest.

The project was completed as part of an MSc Machine Learning coursework.

## Datasets
Two datasets were used:
- A classification dataset: Predicting stroke occurrence (Yes/No).
- A regression dataset: Predicting supermarket organic products spending amount.
  
(Dataset used for the project is from a public source and is in Chinese.)

Detailed variable descriptions are provided in the `Codebook/` directory.


## Methods
For both tasks, the following steps were applied:
- Data preprocessing and feature engineering
- Model training and hyperparameter tuning
- Performance evaluation using appropriate metrics

Models compared:
- Logistic Regression/ Linear Regression
- CART (Decision Tree)
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest (RF)

## Evaluation Metrics
- Classification: Accuracy, Precision, Sensitivity, Specificity, F1-Score, AUC, Confusion Matrix
- Regression: MAE, MAPE, MSE, RMSE

## Results
Results and analysis are presented in the notebooks and saved in the `results/` directory.

## Tech Stack
- Python
- NumPy, Pandas
- Scikit-learn

## Notes
This repository is intended for demonstration and educational purposes.

Project completed in 2022 during MSc studies in Taiwan.

# Customer Churn Prediction

A machine learning project focused on predicting telecom customer churn using exploratory data analysis, feature engineering, model comparison, cross-validation, and hyperparameter tuning.

## Overview

The project analyzes customer demographics, services, billing information, and contract details to identify factors influencing customer churn and build predictive machine learning models.

## Dataset

The dataset contains customer information including:

- Demographics
- Contract Details
- Internet Services
- Payment Methods
- Monthly Charges
- Total Charges
- Customer Tenure
- Churn Status

## Project Workflow

- Data Cleaning
- Missing Value Analysis
- Exploratory Data Analysis (EDA)
- Label Encoding
- Feature Scaling
- Correlation Analysis
- Multicollinearity Check using VIF
- Model Training
- Model Evaluation
- K-Fold Cross Validation
- Feature Importance Analysis
- Hyperparameter Tuning

## Exploratory Data Analysis

Key observations from the analysis:

- Customers with month-to-month contracts are more likely to churn.
- Customers with higher monthly charges are more likely to churn.
- New customers are more likely to churn.

## Models Evaluated

- Logistic Regression
- Linear SVM
- Kernel SVM
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting
- Voting Classifier

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- F2 Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve

## Validation Techniques

- Train-Test Split
- K-Fold Cross Validation
- ROC-AUC Comparison

## Hyperparameter Tuning

RandomizedSearchCV was applied on:

- AdaBoost
- Gradient Boosting

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-Learn
- XGBoost
- Statsmodels

## Repository Structure

```text
├── customer_churn_prediction.py
├── data.csv
├── README.md
```

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Feature Engineering
- Machine Learning
- Model Comparison
- Cross Validation
- Hyperparameter Tuning
- Feature Importance Analysis

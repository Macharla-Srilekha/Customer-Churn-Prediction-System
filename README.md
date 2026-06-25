# Customer Churn Prediction System

## Overview

The Customer Churn Prediction System is a Machine Learning project designed to predict whether a customer is likely to leave (churn) or continue using a service. Customer retention is crucial for businesses, as acquiring new customers is often more expensive than retaining existing ones. This project analyzes customer behavior and subscription data to identify customers who are at risk of churning.

## Problem Statement

Companies often face revenue loss when customers discontinue their services. The objective of this project is to build a predictive model that can identify potential churners based on customer demographics, subscription details, tenure, service usage, and billing information.

## Dataset

The project uses the Telco Customer Churn Dataset, which contains customer information such as:

* Customer ID
* Gender
* Senior Citizen Status
* Partner and Dependents Information
* Tenure
* Phone Service
* Internet Service
* Contract Type
* Monthly Charges
* Total Charges
* Churn Status (Target Variable)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

## Project Workflow

### 1. Data Collection

* Imported the Telco Customer Churn dataset.
* Loaded and explored customer information.

### 2. Data Preprocessing

* Removed unnecessary columns such as Customer ID.
* Handled missing values.
* Converted categorical variables into numerical values using Label Encoding.
* Prepared the dataset for machine learning.

### 3. Exploratory Data Analysis (EDA)

Performed data visualization to understand customer behavior:

* Churn Distribution Analysis
* Monthly Charges vs Churn
* Tenure vs Churn
* Correlation Heatmap
* Customer Distribution Charts

### 4. Feature Engineering

* Created meaningful features for better prediction.
* Selected important variables influencing customer churn.

### 5. Model Building

Implemented multiple classification algorithms:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

### 6. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Confusion Matrix

## Results

The Random Forest Classifier achieved strong performance in predicting customer churn and identifying customers who are likely to discontinue the service. The model can assist businesses in taking proactive retention measures and improving customer satisfaction.

## Visualizations Included

* Churn Distribution Graph
* Monthly Charges Analysis
* Tenure Analysis
* Correlation Heatmap
* Feature Importance Visualization
* Actual vs Predicted Comparison
* Confusion Matrix



## Conclusion

This project demonstrates how Machine Learning can be used to analyze customer behavior and predict churn. By identifying customers who are likely to leave, businesses can take preventive actions, improve retention strategies, and enhance overall revenue growth.



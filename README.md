Customer Churn Prediction
Overview
This project focuses on predicting customer churn using machine learning techniques. The dataset consists of customer demographics, account information, and banking details. The goal is to classify customers as either likely to churn or remain loyal based on various features.

Features
Data Preprocessing:

Handling missing values
Encoding categorical variables
Feature scaling using MinMaxScaler
Exploratory Data Analysis (EDA):

Data distribution visualization (histograms)
Correlation matrix and heatmaps
Pair plots for class separation analysis
Model Training:

Logistic Regression
Support Vector Classifier (SVC)
K-Nearest Neighbors (KNN)
Decision Tree Classifier
Random Forest Classifier
Dataset
The dataset used is Churn_Modelling.csv, which includes customer information such as:
Credit score
Age
Balance
Number of products
Tenure
Geography
Gender
Estimated salary
Churn label (Exited or Not)
Dependencies
To run this notebook, install the required Python libraries:

bash
Copy
Edit
pip install numpy pandas matplotlib seaborn scikit-learn
Usage
Load the dataset and preprocess it.
Perform exploratory data analysis to understand key trends.
Train multiple machine learning models and evaluate their performance.
Compare different classifiers and determine the best model for churn prediction.
Results & Insights
Feature importance can be analyzed through Decision Trees and Random Forests.
Age, credit score, and balance significantly impact customer churn.
Model performance can be evaluated using accuracy, precision, recall, and F1-score.
Future Improvements
Hyperparameter tuning for better model performance.
Implementing deep learning models for higher accuracy.
Deployment of the model as a web application.

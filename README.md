# titanic-survival-prediction
Titanic Survival Prediction Documentation
Overview
This Python script is designed to perform survival prediction on the Titanic dataset. The script covers various steps including data loading, preprocessing, feature engineering, model training, and evaluation. It utilizes machine learning techniques, specifically logistic regression, to predict survival outcomes based on passenger attributes.

Contents
Data Loading
Data Exploration
Data Preprocessing and Feature Engineering
Label Encoding
Train-Test Split
Feature Selection
Model Training and Evaluation
Visualization
Performance Metrics
Documentation (TODO)
Requirements
Python 3.x
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels
Usage
Ensure that you have Python installed on your system along with the required libraries mentioned above.
Download the Titanic dataset (Titanic-Dataset.csv) and save it in the same directory as the script.
Run the script by executing python titanic_survival_prediction.py in your terminal or command prompt.
The script will perform data preprocessing, model training, and evaluation. It will display various metrics and visualizations to assess the model's performance.
Functionality Details
Data Loading: Loads the Titanic dataset into a pandas DataFrame.
Data Exploration: Provides an overview of the dataset including the first few rows, column names, and unique values.
Data Preprocessing and Feature Engineering: Cleans the data by handling missing values and creates new features such as FamilySize, CategoricalFare, and CategoricalAge.
Label Encoding: Encodes categorical variables into numerical values.
Train-Test Split: Splits the dataset into training and testing sets.
Feature Selection: Uses Recursive Feature Elimination (RFE) with Linear Regression to select the most important features.
Model Training and Evaluation: Trains a logistic regression model and evaluates its performance using various metrics such as accuracy, confusion matrix, ROC curve, and classification report.
Visualization: Plots ROC curve and heatmaps for confusion matrices.
Performance Metrics: Calculates and displays performance metrics such as accuracy, recall, and classification report.
Future Improvements
Include additional machine learning algorithms for comparison.
Implement hyperparameter tuning for model optimization.
Enhance documentation with detailed explanations of each step and function.

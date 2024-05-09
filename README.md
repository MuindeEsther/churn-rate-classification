# Telco Customer Churn Prediction
## Project Overview

This project focuses on building a machine learning model to predict customer churn for a telecommunications company. The goal is to identify customers who are likely to discontinue their services, allowing the company to take proactive measures to retain them.

## Dataset

The dataset used in this analysis contains various customer attributes along with their churn status. It has been sourced from Kaggle and includes the following key features: customer demographics, account information, and service details. All necessary preprocessing steps, such as handling missing values and encoding categorical variables, were performed to prepare the data for modeling.

## Methodology
### Data Preprocessing

** Handling Missing Values: The dataset was checked for missing values, and necessary imputations were made (although the initial dataset had no missing values).
** Encoding Categorical Variables: Non-numeric columns were converted to numerical format using label encoding to facilitate model training.

### Exploratory Data Analysis (EDA)

** Analyzed the churn distribution to understand the baseline churn rate.
** Visualized relationships between customer attributes and churn to identify potential predictors.

### Model Building

** Handling Data Imbalance: Implemented SMOTE to address the imbalance in the churn classes, ensuring the model learns equally from both classes.
** Model Training: Trained multiple models including Decision Tree, Random Forest, and XGB Classifier.
** Model Evaluation: Evaluated models based on accuracy, F1 score, and confusion matrices. Focused on F1 score to prioritize the reduction of false negatives.

## Results

The Random Forest Classifier emerged as the most effective model, achieving the highest accuracy and F1 score among the tested models. The detailed performance metrics for each model are included in the analysis.

## Conclusion

The analysis indicates that the Random Forest Classifier is highly effective for predicting customer churn. Given the cost implications of customer churn, the model can be a valuable tool for identifying at-risk customers and enabling targeted customer retention strategies.

## Future Work

Further improvements can be explored through:

** Feature Engineering: More sophisticated feature engineering techniques could be applied to extract additional predictive power from the data.
** Model Optimization: Further tuning of model parameters could improve performance, particularly in minimizing false negatives.
** Deployment: The model could be integrated into a live environment to make real-time predictions and track its performance over time.

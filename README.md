# Predictive_Lead_Scoring_for_Edtech

## Problem Statement:
An edtech company seeks to improve its customer acquisition strategy by predicting which leads are likely to convert into paying customers. By analyzing historical data, the company aims to identify the key factors influencing lead conversion rates to optimize marketing efforts and increase revenue.

## Preparation:
The dataset includes various features related to leads, such as occupation, Lead Source, email subscription status, last activity, and time spent on site. For model building, we will focus on these relevant features to effectively predict lead conversion.

## Objective:
The objective is to assess the predictive power of these variables in forecasting lead conversions by building a predictive model using logistic refgression.

## Business Goal:
Develop a predictive model to classify leads as likely to convert or not based on available features. This model will assist the management in refining marketing strategies, allocating resources effectively, and enhancing overall conversion rates. Additionally, it will provide insights into the factors that drive customer engagement and conversions.

## Solution:
A Logistic Regression model will be utilized to identify and evaluate the significant factors affecting lead conversion. This model will help understand customer behavior and inform strategic marketing decisions for the edtech company.

## What is Logistic Regression?
Logistic regression is a statistical method used for binary classification tasks. It estimates the probability of a binary outcome based on one or more predictor variables. The model uses a logistic function to model the relationship between the dependent variable and independent variables. The goal is to find the best-fitting model that predicts the probability of the target class for new data points. Logistic regression is widely used due to its simplicity, interpretability, and effectiveness in binary classification problems.

## Libraries Used:
- **Numpy:** For numerical computations and handling missing values.
- **Pandas:** For data manipulation and cleaning.
- **Matplotlib:** For basic data visualization.
- **Seaborn:** For advanced data visualization and pattern discovery.
- **Stats-models:** For building, and tuning machine learning models.
- **Scikit-learn:** For evaluating the models

## Contents:
1. Importing Dataset
2. Data Understanding
3. Data Cleaning
   - 3.1. Handling missing values - Dropping
   - 3.2. Handling missing values - Imputing
       - 3.2.1. Imputing Categorical Columns
       - 3.2.2. Imputing Numerical Columns
    - 3.3. Handling Duplicates and Grouping
4. Exploratory Data Analysis (EDA)
   - 4.1. Univariate Analysis
       -  4.1.1. Categorical Variables
       -  4.1.2. Numerical Variables
   - 4.2. Bivariate Analysis
   - 4.3. Multi-variate Analysis
5. Data Preparation
     - 5.1. One-Hot Encoding
          - 5.1.1. Merging the dataframes
     - 5.2. Train-Test Split
     - 5.3. Addressing Class Imbalance - SMOTE
     - 5.4. Feature Scaling - Standardization
6. Model Building
     - 6.1. Recursive Feature Elimination (RFE)
     - 6.2. VIF
     - 6.3. Model Evaluation
     - 6.4. Plotting the ROC Curve
     - 6.5. Finding the Optimal cut off point
7. Predicting on the Test set
     - 7.1. Preparing the test set
     - 7.2. Evaluation on Test set Conclusion








# Predicting Income Levels Using Machine Learning

## Project Overview

This project focuses on predicting whether an individual earns more than $50K annually using demographic and socioeconomic data.

The goal was to:

Perform Exploratory Data Analysis (EDA)

Clean and preprocess real-world data

Engineer meaningful features

Train classification models

Evaluate model performance

# Dataset

The dataset contains over 32,000 records with features such as:

Age

Education

Occupation

Marital status

Hours worked per week

Capital gain/loss

Income (target variable)


# Data Cleaning

Replaced missing values (?) with NaN

Imputed missing categorical values using mode

Ensured no missing values remained

Exploratory Data Analysis (EDA)

Key insights:

Individuals working more hours are more likely to earn >50K

Higher education levels strongly correlate with higher income

Most individuals work ~40 hours/week

Income distribution is imbalanced (more ≤50K earners)

# Feature Engineering
Created net_capital (gain – loss)

Binned age into groups (Young, Adult, Senior, Elder)

Combined education levels for better representation

# Models Used
Logistic Regression

Decision Tree

Random Forest

KMeans clustering for feature enhancement

Model Evaluation

Models were evaluated using:
Accuracy

Precision

Recall

F1-score

ROC-AUC

# Key Insights
Education level is a strong predictor of income

Working hours significantly influence income level

Feature engineering improved model performance

Class imbalance affects prediction accuracy

# Conclusion
This project demonstrates the ability to:

Handle real-world messy data

Perform deep exploratory analysis

Build and evaluate classification models

Extract meaningful, business-relevant insights

# Tools Used
Python

Pandas

NumPy

Scikit-learn

Seaborn & Matplotlib

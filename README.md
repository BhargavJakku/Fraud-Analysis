# Phising Website Detecting using MLmodel

**Project Goal:**

Develop a machine learning model to classify websites as phishing or legitimate based on various features extracted from their URLs and content.

**Data Preprocessing:**

Exploratory Data Analysis: Basic statistics, feature distributions, missing value analysis.

**Data Cleaning:**

1. Dropped features with constant or missing values.
2. Replaced missing values with NaN.
3. Dropped features with more than 50% missing values (potential information loss).
4. Imbalanced Class Handling: Oversampled the minority class (phishing) using SMOTE to address the imbalance.

**Feature Engineering:**

1. Extracted categorical features from URLs (e.g., presence of email in URL, server-client domain).
2. Created counterplots to visualize distributions of categorical features.
   
**Machine Learning Modeling:**

1. **Algorithms**:
     1. Decision Tree Classifier
     2. K-Nearest Neighbors (KNN)
     3. Logistic Regression
     4. Random Forest Classifier

2. **Hyperparameter Tuning**: Used GridSearchCV to find optimal hyperparameters for each model.
   
3. **Evaluation**: Reported accuracy, precision, recall, and ROC AUC for each model.

**Results:**

All models achieved reasonable performance, with Random Forest generally performing the best.
ROC curves were plotted to compare model performance visually.


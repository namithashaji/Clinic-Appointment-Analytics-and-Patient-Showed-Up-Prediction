# Clinic Appointment Analytics and Patient No-Show Prediction

A complete end-to-end Machine Learning project focused on analyzing healthcare appointment data and predicting whether a patient will miss a scheduled clinic appointment.

This project combines data preprocessing, exploratory data analysis (EDA), feature engineering, classification modeling, hyperparameter tuning, and performance evaluation to help healthcare organizations reduce appointment no-shows and improve operational efficiency.

---

# Project Overview

Healthcare providers frequently experience missed appointments from patients, which negatively impacts:

- Doctor availability
- Clinic workflow
- Revenue
- Patient care quality

This project aims to analyze patient appointment behavior and predict no-show occurrences using Machine Learning techniques.

---

# Objectives

- Perform data cleaning and preprocessing
- Conduct exploratory data analysis (EDA)
- Engineer meaningful features from appointment data
- Train multiple classification models
- Compare model performance using evaluation metrics
- Tune model hyperparameters

---

# Dataset Information

The dataset contains historical clinic appointment records with patient-related and appointment-related information.

Dataset link: https://www.kaggle.com/datasets/wajahat1064/healthcare-appointment-dataset/data

---

# Technologies Used

## Programming Language
- Python

## Libraries
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

# Project Workflow

## 1. Data Collection
- Loaded healthcare appointment dataset
- Inspected structure and data types

## 2. Data Cleaning
- Removed irrelevant columns
- Handled missing values
- Removed invalid age values
- Removed duplicates
- Converted date columns to datetime format

## 3. Exploratory Data Analysis (EDA)
Performed:
- Target distribution analysis
- Correlation heatmap
- Class imbalance analysis
- Feature relationship analysis

## 4. Feature Engineering
Created new features such as:
- Waiting_Days
- Appointment_Month
- Appointment_DayOfWeek

## 5. Data Preprocessing
- Label Encoding
- One-Hot Encoding
- Feature Scaling
- Train-Test Split

## 6. Model Building
Implemented multiple Machine Learning models:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- SVM

## 7. Model Evaluation
Evaluated models using:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve

## 8. Hyperparameter Tuning
Used:
- GridSearchCV
- Cross Validation

to improve model performance and generalization.

---

# Exploratory Data Analysis Highlights

## Target Distribution
The dataset shows class imbalance where the majority of patients attended appointments.

## Correlation Analysis
Key observations:
- Waiting days showed stronger correlation with no-show behavior
- Most variables had weak linear correlations
- Attendance behavior depends on multiple interacting factors

## Important Insights
- Longer waiting periods increase the probability of missed appointments
- SMS reminders influence patient attendance

---

# Best Performing Model

## Gradient Boosting Classifier

The Gradient Boosting model achieved the best overall performance based on:

- F1 Score
- ROC-AUC Score

---

# Model Evaluation Metrics

## Why F1 Score?
The dataset contains class imbalance, making F1 Score more reliable than accuracy alone.

## ROC-AUC
ROC-AUC was used to evaluate the model’s ability to distinguish between patients who would attend and miss appointments.

---

# Key Business Insights

- Patients with longer waiting times are more likely to miss appointments
- Appointment reminder systems can improve attendance
- Predictive analytics can help clinics optimize scheduling
- High-risk patients can be targeted for proactive follow-up

---


# Conclusion

This project successfully developed a Machine Learning pipeline capable of predicting patient appointment no-shows using healthcare appointment data.

Through data preprocessing, exploratory analysis, feature engineering, model comparison, and evaluation, the project demonstrates how predictive analytics can improve healthcare scheduling efficiency and resource management.

The Gradient Boosting model emerged as the best-performing model with strong classification performance and predictive capability.

---

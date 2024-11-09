# Heart Disease Prediction using Logistic Regression

This project is a machine learning model that predicts heart disease events (death events) in patients using logistic regression. The model is trained on the Heart Failure Clinical Records Dataset, performing classification to identify high-risk patients based on various medical indicators.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Materials](#project-materials)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Results](#results)

## Overview

This project implements a logistic regression model to predict the probability of a heart disease event occurring. Key techniques include data preprocessing, splitting into training and testing sets, model training, evaluation, and saving the trained model for future use. The project also includes visualizations of performance metrics like confusion matrix, ROC curve, and precision-recall curve.

## Dataset

The dataset used in this project is the [Heart Failure Clinical Records Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+failure+clinical+records), available on UCI's Machine Learning Repository. It contains various clinical records of patients, including:

- Age
- Anaemia
- creatinine_phosphokinase
- diabetes
- high_blood_pressure
- platelets
- Sex
- Serum creatinine
- Serum sodium
- Ejection fraction
- smoking
- DEATH_EVENT (target variable)
- time

**Target Variable:** `DEATH_EVENT` – Binary indicator for whether the patient experienced a heart disease-related event.

## Project Materials

This repository contains the following materials:

1. **Data Preprocessing and Splitting**: Code to clean and split the dataset into training and testing subsets.
   
2. **Logistic Regression Model**: Implementation of the logistic regression model for predicting the likelihood of a heart disease event.

3. **Model Training and Evaluation Script**: A Python script that trains the model on the dataset and evaluates its accuracy and other metrics.

4. **Saved Model**: The trained logistic regression model is saved using the `pickle` library for future use in predictions.

5. **Visualizations**:
   - **Confusion Matrix**: Displays the classification accuracy in terms of true and false predictions.
   - **ROC Curve**: Shows the trade-off between the true positive rate and the false positive rate.
   - **Precision-Recall Curve**: Illustrates the balance between precision and recall.

6. **User Prediction Script**: A script for user input, which allows making predictions for new patients based on their medical data.

## Model Training and Evaluation

- **Model:** Logistic Regression
- **Data Split:** 70% training, 30% testing
- **Performance Metrics:**
  - Confusion Matrix
  - ROC Curve and AUC (Area Under Curve)
  - Precision-Recall Curve

## Results

The logistic regression model achieves an accuracy of approximately `85%` on the test set. Key performance visualizations (Confusion Matrix, ROC, and Precision-Recall curves) provide further insights into the model’s effectiveness and reliability in predicting heart disease events.


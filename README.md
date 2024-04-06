# Breast Cancer Prediction Using Ensembling Techniques

## Overview
This project aims to predict whether a patient has breast cancer or not using ensembling techniques. Ensemble learning involves combining multiple machine learning models to improve predictive performance. In this project, we explore Random Forest, Bagging, Adaboost, and SVM classifiers to predict breast cancer based on various features extracted from breast mass cell nuclei.

## Problem Statement
Given details of cell nuclei extracted from breast masses, the goal is to classify patients into two categories: 'Benign' (no cancer) and 'Malignant' (cancer).

## Dataset Information
The dataset consists of several features describing the properties of cell nuclei, along with the target variable 'Diagnosis' indicating the presence or absence of cancer. Features include mean radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, and fractal dimension.

## Scope
- Analyzing the dataset and exploring relationships among variables
- Pre-processing the data for modeling
- Training various ensemble classifiers (Random Forest, Bagging, Adaboost) and SVM
- Evaluating model performance using accuracy, precision, recall, F1-score, ROC-AUC, sensitivity, and specificity
- Tuning hyperparameters to improve model performance

## Approach
1. Data exploration and preprocessing
2. Splitting the dataset into training and testing sets
3. Training Random Forest, Bagging, Adaboost, and SVM classifiers
4. Evaluating model performance using various metrics
5. Hyperparameter tuning to optimize model performance

## Evaluation Metrics
- **Accuracy**: Overall correctness of the model
- **Precision**: Proportion of true positive predictions among all positive predictions
- **Recall**: Proportion of true positive predictions among all actual positive instances
- **F1-score**: Harmonic mean of precision and recall
- **ROC-AUC**: Area under the receiver operating characteristic curve
- **Sensitivity**: True positive rate, proportion of actual positive instances correctly predicted as positive
- **Specificity**: True negative rate, proportion of actual negative instances correctly predicted as negative

## Conclusion
Ensemble techniques, specifically Random Forest and Adaboost, show promise in predicting breast cancer based on cell nuclei features. These models demonstrate high accuracy and performance across multiple evaluation metrics. Further research and experimentation can explore additional features and algorithms to improve predictive accuracy.




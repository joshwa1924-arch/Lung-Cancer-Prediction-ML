# Lung Cancer Prediction Using Machine Learning

This project focuses on predicting lung cancer using health, lifestyle, and symptom-based survey data. The study compares multiple machine learning classification models to identify the most effective approach for lung cancer prediction.

## Project Overview

The dataset contains 309 records with demographic, lifestyle, and symptom-related variables, including age, gender, smoking, yellow fingers, alcohol consumption, peer pressure, fatigue, allergies, wheezing, coughing, chest pain, swallowing difficulty, chronic disease, and shortness of breath. The target variable is Lung Cancer (Yes/No). :contentReference[oaicite:0]{index=0}

The project includes exploratory data analysis, statistical testing, data preprocessing, machine learning model development, feature analysis, and performance comparison.

## Objectives

- Predict lung cancer based on survey-based health and lifestyle information.
- Compare different machine learning classification algorithms.
- Identify important factors associated with lung cancer prediction.
- Evaluate models using multiple classification metrics.
- Determine the best-performing model for the given dataset.

## Exploratory Data Analysis

EDA was performed to understand relationships between symptoms, lifestyle factors, demographic variables, and lung cancer. Bar charts, count plots, and statistical tests were used to examine the dataset.

The analysis found statistically significant relationships for several variables, including yellow fingers, allergy, wheezing, fatigue, peer pressure, coughing, alcohol consumption, swallowing difficulty, and chest pain. Gender, smoking, chronic disease, and shortness of breath did not show statistically significant relationships in this particular dataset. :contentReference[oaicite:1]{index=1}

## Machine Learning Models

The following classification models were developed and evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- XGBoost
- Artificial Neural Network (ANN)
- Naïve Bayes

These models were evaluated using Accuracy, Sensitivity, Specificity, and ROC-AUC. :contentReference[oaicite:2]{index=2}

## Model Performance

Logistic Regression:
  Accuracy = 90.32%
  AUC = 0.949
  Sensitivity = 96.30%
  Specificity = 50.00%

SVM:
  Accuracy = 90.32%
  AUC = 0.949
  Sensitivity = 94.44%
  Specificity = 62.50%

Decision Tree:
  Accuracy = 87.10%
  AUC = 0.943
  Sensitivity = 88.89%
  Specificity = 75.00%

Random Forest:
  Accuracy = 91.94%
  AUC = 0.947
  Sensitivity = 94.44%
  Specificity = 75.00%

XGBoost:
  Accuracy = 87.10%
  AUC = 0.924
  Sensitivity = 90.74%
  Specificity = 62.50%

ANN:
  Accuracy = 88.71%
  AUC = 0.942
  Sensitivity = 92.59%
  Specificity = 62.50%

Naïve Bayes:
  Accuracy = 85.48%
  AUC = 0.938
  Sensitivity = 90.74%
  Specificity = 50.00%

The reported comparison shows that **Random Forest achieved the highest accuracy (91.94%)**, while Logistic Regression and SVM achieved the highest AUC (0.949) among the evaluated models. :contentReference[oaicite:3]{index=3}

## Key Findings

- Random Forest achieved the highest overall accuracy.
- Logistic Regression and SVM demonstrated strong ROC-AUC performance.
- Several symptoms and lifestyle factors showed significant associations with lung cancer in this dataset.
- Feature importance analysis was used to understand which variables contributed most to model predictions.
- The study demonstrates how machine learning can be applied to survey-based healthcare data for lung cancer risk prediction.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Exploratory Data Analysis
- Statistical Testing
- Machine Learning
- Data Visualization

## Conclusion

This project demonstrates a comparative machine learning approach to lung cancer prediction using survey-based health, lifestyle, and symptom data. Multiple classification algorithms were developed and evaluated to identify differences in predictive performance and understand important risk-related features.

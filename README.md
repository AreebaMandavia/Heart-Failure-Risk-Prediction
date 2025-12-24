# Heart-Failure-Risk-Prediction
## Overview
Heart disease is a leading cause of death worldwide. Early detection can save lives. This project implements a predictive system using ML models to classify patients into "High" ,"Moderate" or "Low" categories based on various clinical features.

## Dataset

The dataset used is `heart_disease_data.csv`, which contains 303 records and 14 features including:

* Age
* Sex
* Chest pain type (`cp`)
* Resting blood pressure (`trestbps`)
* Cholesterol (`chol`)
* Fasting blood sugar (`fbs`)
* Resting ECG results (`restecg`)
* Maximum heart rate achieved (`thalach`)
* Exercise-induced angina (`exang`)
* ST depression (`oldpeak`)
* Slope of ST segment (`slope`)
* Number of major vessels (`ca`)
* Thalassemia (`thal`)
* Target variable (`target`): 1 = Heart Disease, 0 = No Heart Disease

## Features

The project includes:

* Data preprocessing
* Exploratory Data Analysis (EDA) using seaborn and matplotlib
* Correlation heatmaps, pair plots, and distribution plots
* Analysis of categorical and numerical features

---

## Models Used

The following models were trained and evaluated:

1. **Logistic Regression**
2. **Naive Bayes (GaussianNB)**
3. **Support Vector Machine (SVM)**
4. **XGBoost Classifier**
5. **Neural Network (Keras Sequential Model)**

## Exploratory Data Analysis

* Correlation matrix to identify feature relationships
* Boxplots and histograms to visualize feature distribution by target
* Pairplots for numerical features vs target
* Analysis of categorical feature counts
  
## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 88%      |
| Naive Bayes         | 87%      |
| SVM                 | 70%      |
| XGBoost             | 82%      |
| Neural Network      | 87%      |


## Future Work

* Implementing a web-based or mobile interface for real-time predictions
* Using additional features or larger datasets for improved accuracy
* Include recommendations using LLM
Do you want me to do that?

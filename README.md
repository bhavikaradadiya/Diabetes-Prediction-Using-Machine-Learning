# Diabetes Prediction Using Machine Learning
This project applies machine learning techniques to predict whether an individual is likely to have diabetes based on several medical attributes such as glucose level, BMI, insulin level, and others. 

## The goal of the project is to:  

Explore the dataset and understand feature patterns,

Preprocess and clean the data,

Train multiple classification models,

Compare performance metrics,

Identify the best-performing algorithm

📌 Dataset

The dataset contains 768 records with 8 input features and 1 target variable:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Outcome (0 = No diabetes, 1 = Diabetes)

Dataset Source:
Publicly available Pima Indians Diabetes Dataset (Kaggle/UCI).

📊 Project Workflow
1. Exploratory Data Analysis (EDA)

Histograms for all numerical features

Correlation heatmap

Zero-value detection in medical fields (treated as missing values)

2. Data Cleaning

Replace invalid zero values using mean/median imputation

Standardize features using StandardScaler

3. Machine Learning Models

The following classification models were implemented:

Logistic Regression

Random Forest

Decision Tree

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

4. Model Evaluation

Metrics used:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

5. Model Comparison

After evaluating all models, SVM produced the highest accuracy in this project.

## 📈 Results Summary
Model	Accuracy
Logistic Regression	~0.74
Random Forest	~0.74
Decision Tree	~0.75
SVM	~0.76 (Best)
KNN	~0.66

SVM demonstrated strong performance and balanced metrics, making it the preferred model for this dataset.

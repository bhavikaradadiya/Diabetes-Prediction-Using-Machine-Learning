# Diabetes Prediction Using Machine Learning
This project applies machine learning techniques to predict whether an individual is likely to have diabetes based on several medical attributes such as glucose level, BMI, insulin level, and others. 

## The goal of the project is to:  

Explore the dataset and understand feature patterns,

Preprocess and clean the data,

Train multiple classification models,

Compare performance metrics,

Identify the best-performing algorithm

## 📌 Dataset

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

## Dataset Source:
Publicly available Pima Indians Diabetes Dataset (Kaggle/UCI).

## 📊 Project Workflow
### 1. Exploratory Data Analysis (EDA)

Histograms for all numerical features

Correlation heatmap

Zero-value detection in medical fields (treated as missing values)

### 2. Data Cleaning

Replace invalid zero values using mean/median imputation

Standardize features using StandardScaler

### 3. Machine Learning Models

The following classification models were implemented:

Logistic Regression

Random Forest

Decision Tree

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

### 4. Model Evaluation

### Metrics used:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

### 5. Model Comparison

After evaluating all models, SVM produced the highest accuracy in this project.

### 📈 Results Summary
Model	Accuracy
Logistic Regression	~0.74

Random Forest	~0.74

Decision Tree	~0.75

SVM	~0.76 (Best)

KNN	~0.66

 SVM demonstrated strong performance and balanced metrics, making it the preferred model for this dataset.

 ### 🛠️ Technologies Used

Python

NumPy

Pandas

Scikit-learn

Matplotlib

Seaborn

### Notebook Outline (diabetes_analysis.ipynb)

### 1. Import Libraries
### 2. Load Dataset
### 3. Check for Zero Values
### 4. Handle Missing/Zero Values (Imputation)
### 5. EDA

Histograms

Correlation matrix

### 6. Data Preprocessing

Train-test split

Scaling

### 7. Train Models

Logistic Regression

Random Forest

Decision Tree

SVM

KNN

### 8. Evaluate

Classification report

Confusion matrices

### 9. Compare Models

Create DataFrame of metrics

Bar plot of accuracy

### 10. Conclusion

Select best model (SVM)

##  Reference

Provost, F. and Fawcett, T., Data Science for Business 2013.

Dowd, P.A., 2023. Accuracy and Precision. In Encyclopedia of Mathematical Geosciences (pp. 1-4). Cham: Springer International Publishing

Hand, D.J., Christen, P. & Kirielle, N. F*: an interpretable transformation of the F-measure. Mach Learn 110, 451–456 (2021). https://doi.org/10.1007/s10994-021-05964-1

Breiman, L., 2001. Random forests. Machine Learning, 45(1), pp.5-32. Available at: https://doi.org/10.1023/A:1010933404324

Mukhiya, S.K. and Ahmed, U., 2020. Hands-On Exploratory Data Analysis with Python: Perform EDA techniques to understand, summarize, and investigate your data. Packt Publishing Ltd.

Albon, C., 2018. Machine learning with python cookbook: Practical solutions from preprocessing to deep learning. " O'Reilly Media, Inc.".

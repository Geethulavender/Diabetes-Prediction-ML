# Diabetes Prediction Using Machine Learning

🧩 Project Overview
This project focuses on predicting the likelihood of a person having diabetes based on health-related features using Machine Learning techniques.
We start with basic Linear Regression and then build a stronger Random Forest model.
Model explainability is performed using SHAP values.

📂 Dataset
Source: Pima Indians Diabetes Dataset

File Used: diabetes.csv

Description: The dataset consists of features such as:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Outcome (Target Variable)


⚙️ Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

SHAP

🛠️ Project Workflow
Data Cleaning

Handle missing values

Deal with outliers

Exploratory Data Analysis (EDA)

Visualize key variables

Understand feature correlations

Modeling

Apply Linear Regression (initial baseline)

Build and fine-tune Random Forest Classifier

Hyperparameter tuning with GridSearchCV

Model Explainability

Use SHAP values

Create force plots, beeswarm plots, and dependence plots


📈 Results
Model                       	| Metric             	| Score
Linear Regression	            R² Score	              0.28
Random Forest Classifier    	Accuracy	              85%
Random Forest Classifier	    ROC AUC Score         	0.90



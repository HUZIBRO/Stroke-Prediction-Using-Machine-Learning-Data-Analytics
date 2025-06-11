# 🧠 Stroke Prediction Using Machine Learning & Data Analytics

This project applies a complete data science and machine learning workflow to predict the likelihood of stroke occurrence based on a patient's health and lifestyle data. It demonstrates core competencies in data preparation, exploratory data analysis (EDA), feature engineering, and binary classification using Logistic Regression and Decision Tree Classifier.

## 🔍 Project Objectives

Explore health data to identify factors linked with stroke risk

Build predictive models to classify stroke vs. no-stroke cases

Evaluate and compare models using classification metrics

## 📃 Dataset Overview

Source: healthcare-dataset-stroke-data.csv

Features: Age, Gender, BMI, Smoking Status, Hypertension, Heart Disease, Glucose Level, etc.

Target: stroke (binary classification)

## 📊 Workflow Summary

1. Data Loading & Initial Exploration

Loaded data with pandas, inspected structure using .head(), .info(), .describe()

Dropped the id column as it was non-informative

2. Data Cleaning & Encoding

Checked and removed missing values using .isna() and .dropna()

Encoded categorical features (gender, ever_married, work_type, etc.) using label encoding

3. Exploratory Data Analysis (EDA)

Created histograms, bar plots, and count plots with seaborn and matplotlib

Analyzed feature distributions and visualized stroke distribution across categories

4. Feature Selection

Computed correlation matrix and plotted heatmap

Selected features with strong correlation to stroke for model input

5. Model Building & Evaluation

Split data into training and test sets (70/30)

### Trained two classifiers:

1. Logistic Regression

2. Decision Tree Classifier

### Evaluated performance using:

Classification report (precision, recall, F1-score)

Confusion matrix (visualized)

Accuracy score comparison

## 📊 Tools & Libraries

Python

Pandas

NumPy

Seaborn

Matplotlib

Scikit-learn

## 💼 Key Skills Demonstrated

Data wrangling and transformation

EDA and visual pattern recognition

Feature engineering and encoding

Binary classification and model evaluation


# 💼 Adult Income Classification

## 📌 Introduction
This project aims to predict whether an individual's income exceeds a certain threshold using demographic and employment-related features.

## 🎯 Objective
The goal is to build a classification model that predicts income category:
- <=50K
- >50K

## 📊 Dataset Description
The dataset contains 48,842 records with multiple features:

### Numerical Features:
- Age
- fnlwgt
- Educational Number
- Capital Gain
- Capital Loss
- Hours per Week

### Categorical Features:
- Workclass
- Education
- Marital Status
- Occupation
- Relationship
- Race
- Gender
- Native Country

### Target Variable:
- **Income**

## ⚙️ Data Preprocessing
- Handled categorical variables using encoding techniques
- Cleaned and prepared dataset
- Checked for missing values
- Converted target variable into numerical format
- Split data into training and testing sets

## 🤖 Model
- Classification model was applied to predict income category
- Model trained using Scikit-learn

## 📈 Evaluation
- Model performance evaluated using **Accuracy Score**
- Confusion matrix can be added for deeper analysis

## 🚀 Results
- The model achieved a reasonable accuracy
- Demographic features showed impact on income prediction

## 📁 Project Structure

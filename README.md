# 🛳 Titanic - Machine Learning from Disaster

This repository contains a machine learning project based on the famous Titanic dataset from Kaggle. The goal is to predict which passengers survived the Titanic shipwreck using classification algorithms.

## 📁 Project Overview

- Uses the **Kaggle Titanic dataset**
- Implements two main machine learning models:
  - Decision Tree Classifier
  - Random Forest Classifier
- Covers the full data science pipeline:
  - Data cleaning and preprocessing
  - Exploratory data analysis (EDA)
  - Feature engineering
  - Model training and evaluation

## 📊 Features & Techniques

- **Data Cleaning**:
  - Handling missing values in `Age`, `Cabin`, and `Embarked`
- **Feature Engineering**:
  - Extracted `Title` from names
  - Created `FamilySize` and `IsAlone` features
  - Converted categorical variables using label encoding or one-hot encoding
- **EDA**:
  - Visualized survival rates based on features like `Sex`, `Pclass`, `Age`, etc.
- **Modeling**:
  - Compared **DecisionTreeClassifier** and **RandomForestClassifier**
  - Evaluated models using accuracy scores

## 🧰 Libraries Used

- Python 3
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## 📈 Results

- Both models performed well, with **Random Forest** outperforming the Decision Tree on the validation set.
- Feature importance plots highlighted `Sex`, `Pclass`, and `Title` as key indicators of survival.

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Mohamed-Kenawy/Titanic_Project.git
   cd Titanic_Project

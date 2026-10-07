# Titanic Survival Prediction using Decision Tree

A beginner machine learning project that uses a Decision Tree classifier to predict whether a Titanic passenger survived based on passenger characteristics.

## Objective

The objective of this project is to understand and practice the complete machine learning workflow for a binary classification problem using a Decision Tree.

## Dataset

The project uses the **Titanic dataset**, loaded directly from an online CSV source.

### Dataset Details

- **Total samples:** 891
- **Features:** 11 original features
- **Target:** `Survived`

### Target

- `0` → Did not survive
- `1` → Survived

## Features Used

The model uses the following features:

- Passenger Class (`Pclass`)
- Sex
- Age
- Number of Siblings/Spouses (`SibSp`)
- Number of Parents/Children (`Parch`)
- Fare
- Port of Embarkation (`Embarked`)

## Machine Learning Workflow

```text
Online Dataset
      ↓
Data Exploration
      ↓
Missing Value Analysis
      ↓
Feature Selection
      ↓
Missing Value Handling
      ↓
Categorical Encoding
      ↓
Train-Test Split
      ↓
Decision Tree Classifier
      ↓
Prediction
      ↓
Model Evaluation
      ↓
Confusion Matrix
      ↓
Decision Tree Visualization
      ↓
Feature Importance
      ↓
Tree Depth Analysis
# Wine Quality Prediction using Decision Tree

## Overview

This project predicts the quality of red wine using a Decision Tree Classifier.

The dataset contains physicochemical properties of red wine such as acidity, sugar, chlorides, sulphates and alcohol.

## Dataset

The dataset used is the Red Wine Quality dataset.

It contains 1599 wine samples and 12 columns.

### Features

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

### Target

- Quality

## Machine Learning Model

A Decision Tree Classifier is used for wine quality prediction.

The model uses:

- Entropy criterion
- Train-test split
- Stratified sampling
- Hyperparameter tuning using GridSearchCV
- 10-fold cross-validation

## Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix
- ROC-AUC
- Cross-validation
- Learning Curve

## Project Files

```text
ML4.ipynb          → Complete analysis and machine learning implementation
winequality-red.csv → Dataset
requirements.txt   → Required Python libraries
README.md          → Project documentation

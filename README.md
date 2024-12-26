# Machine Learning Pipeline for Classification

## Overview
This project implements a machine learning pipeline for classification tasks using a **Random Forest Classifier**. The pipeline includes data preprocessing, model training, hyperparameter tuning, and evaluation using cross-validation. It is designed to be flexible and efficient, with command-line integration for reproducible results.

---

## Features
- **Data Preprocessing**: Handles missing values, encodes categorical variables, and identifies numerical columns for feature engineering.
- **Model Training and Evaluation**: Trains a Random Forest model and evaluates its performance using **Stratified K-Fold Cross-Validation** with the **F1 Score** metric.
- **Hyperparameter Tuning**: Utilizes **RandomizedSearchCV** to find the optimal model configuration.
- **Command-Line Integration**: Supports command-line arguments for specifying training data, testing data, and saving predictions.

---

## Requirements
- Python 3.7+
- Required Libraries:
  - Pandas
  - NumPy
  - Scikit-learn
  - argparse

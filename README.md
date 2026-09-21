# Diabetes Prediction Using Machine Learning

A machine learning classification project developed to analyze diabetes-related health data and predict diabetes outcomes using multiple classification algorithms.

## Project Overview

This project implements an end-to-end machine learning workflow for diabetes classification. It includes data preprocessing, feature preparation, model training, performance evaluation, model comparison, and prediction on a new sample record.

## Dataset

The project uses `diabetes.csv`, which contains health-related attributes used for binary diabetes classification.

During preprocessing, medically unrealistic zero values in selected features are treated as missing values and replaced using median imputation.

## Machine Learning Models

Four classification algorithms are implemented and compared:

- Logistic Regression
- Decision Tree
- Gaussian Naive Bayes
- Support Vector Machine (SVM)

## Machine Learning Workflow

The project includes:

- Loading the diabetes dataset
- Data preprocessing and missing-value handling
- BMI-based feature engineering
- Train/test splitting
- Feature scaling using StandardScaler
- Training multiple classification models
- Generating predictions
- Comparing model performance
- Predicting the outcome of a new sample record

## Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

## Project Files

- `diabetes_prediction.ipynb` — Main notebook containing preprocessing, model training, evaluation, comparison, and prediction.
- `diabetes.csv` — Dataset used in the project.
- `.gitignore` — Specifies files and folders that Git should ignore.

## How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open `diabetes_prediction.ipynb` using Jupyter Notebook, JupyterLab, or Google Colab.
4. Make sure `diabetes.csv` is in the same directory as the notebook.
5. Run the notebook cells in order.

## Purpose

This academic project was developed to practice an end-to-end machine learning classification workflow, from preparing health-related data to training, evaluating, comparing, and using multiple classification models.

> **Note:** This project is intended for educational purposes and should not be used as a medical diagnostic tool.

## Author

**Jihad Al-Dabet**  
Artificial Intelligence & Data Science Student  
University of Petra

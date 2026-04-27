# Machine Learning Final Project

## Overview
This project compares multiple supervised machine learning models across two datasets:
- Student Performance Dataset
- Customer Purchase Behavior Dataset

The goal is to evaluate how different models perform depending on the structure of the data and the type of prediction task.

---

## Datasets

### Student Performance
- Predicts whether a student passes or fails
- Target variable was converted from final grade (G3) into a binary classification problem
- G1 and G2 were removed to avoid data leakage

### Customer Purchase Behavior
- Predicts whether a customer makes a purchase
- Includes demographic and behavioral features such as income and browsing activity

---

## Models Used
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Multi-Layer Perceptron (MLP)

---

## Methods
- Train/test split (80/20)
- Feature scaling applied where needed
- Hyperparameter tuning performed using GridSearchCV (mainly for KNN)
- Models evaluated using accuracy, confusion matrices, and ROC curves

---

## Key Results
- Logistic Regression performed best on the Student Performance dataset
- MLP performed best on the Customer Purchase dataset
- Model performance varies depending on dataset structure (linear vs non-linear)

---

## Files
- `Final_Project.ipynb` – Full notebook with code, outputs, and analysis  
- `Final_Project_Report.pdf` – Summary report  

---

## Author
Tristan Grote

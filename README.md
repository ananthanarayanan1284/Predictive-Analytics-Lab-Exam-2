# Predictive-Analytics-Lab-Exam-2
Lab Exam 2 Anantanarayanan B DAGIS 253318

## Overview
This repository contains the code and dataset for Lab Exam-2. The objective is to perform a classification task, including Exploratory Data Analysis (EDA), model training, decision boundary visualization, and performance evaluation.

## Files Included
* `Lab_Exam_binary_classification_dataset.csv`: The dataset used for the classification task.
* `LAB_EXAM2_.ipynb`: The main script containing the EDA, modeling, and evaluation.

## Methodology
1. **EDA** – Checked for missing values, removed an extreme outlier, explored class balance, distributions, and correlations.
2. **Model** – Trained a Logistic Regression model with standard scaling and `class_weight='balanced'` to handle class imbalance.
3. **Decision Boundary** – Plotted the decision boundary overlaid on the dataset.
4. **Evaluation** – Reported accuracy, precision, recall, F1, ROC-AUC and  confusion matrix

> **Note:** The dataset has a mild class imbalance (~78% No, ~22% Yes) and low feature-target correlation, which limits the performance of a linear classifier like Logistic Regression. This is discussed in the notebook observations.

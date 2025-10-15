# Leveraging Machine Learning for Breast Cancer Prediction

This repository contains a machine learning project focused on predicting breast cancer malignancy using the Wisconsin Diagnostic Breast Cancer (WDBC) dataset. The project involves data exploration, preprocessing, and the implementation and tuning of various classification models.

## Project Overview

The project workflow, detailed in the `Breast Cancer Prediction.ipynb` Jupyter Notebook, encompasses:
1.  **Data Exploration & Visualization**: Understanding feature distributions and class balance.
2.  **Data Preprocessing**: Preparing the data for modeling through encoding and feature scaling.
3.  **Model Implementation and Tuning**: Building and optimizing several classification models to achieve high performance.

## Dataset

The project uses the `breast_cancer_dataset.csv` file.
* **Features**: 30 real-valued numeric features describing cell nuclei.
* **Target Variable**: `diagnosis` ('M' = Malignant, 'B' = Benign).

## Machine Learning Models and Methodology

A comparative analysis of several classification algorithms was conducted to identify the most effective model for this prediction task.

### Models Implemented

The following machine learning models were trained and evaluated:
* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree Classifier
* Random Forest Classifier

### Model Tuning and Optimization

All implemented models were fine-tuned using hyperparameter optimization techniques to maximize their predictive performance. Among the evaluated models, the **Support Vector Machine (SVM)**, after being optimized with `GridSearchCV`, delivered the best results and was selected as the final model.

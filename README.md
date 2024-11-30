# Machine Learning Cancer Classification

## Overview
This project develops a classification model to predict breast cancer as either malignant or benign using the Wisconsin Breast Cancer Dataset. 
The process includes exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and performance evaluation.

## Workflow

### 1. Data Import and Preparation
- Import the dataset.
- Split the data into X(Features) and y(target).

### 2. Exploratory Data Analysis (EDA)
- Examine data distributions and feature relationships.
- Identify and handle outliers appropriately.

### 3. Data Preprocessing
- Apply `StandardScaler` for standardizing the features.
- Use `SelectKBest` to select the most relevant features for the model.

### 4. Model Implementation
- Develop and configure model pipelines for:
  - `K-Nearest Neighbors (KNN)`
  - `Decision Trees`
  - `Support Vector Machines (SVM)`
  - `Random Forest`

### 5. Hyperparameter Optimization
- Use `GridSearchCV` for hyperparameter tuning with **Macro F1** as the evaluation metric.

### 6. Performance Evaluation
- Assess each model using precision, recall, accuracy, and Macro F1 score.
- Visualize the results and compare the performance of the models.

## Requirements

- **Python Libraries:**
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  

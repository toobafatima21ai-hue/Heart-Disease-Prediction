#  Heart Disease Prediction using Machine Learning

##  Project Overview

This project predicts whether a patient is likely to have heart disease based on various medical attributes from the Heart Disease UCI Dataset. The project applies data preprocessing, exploratory data analysis (EDA), feature engineering, machine learning model training, and performance evaluation to compare different classification algorithms.

The primary objective is to build a reliable classification model that can assist in the early detection of heart disease using patient health information.

---

## Objectives

* Analyze and understand the Heart Disease UCI dataset.
* Perform data cleaning and preprocessing.
* Conduct Exploratory Data Analysis (EDA) to discover patterns and relationships.
* Train and evaluate multiple machine learning models.
* Compare model performance using various classification metrics.
* Visualize results using confusion matrices, ROC curves, feature importance plots, and correlation heatmaps.

---

## Dataset

**Dataset:** Heart Disease UCI Dataset

The dataset contains patient medical information such as:

* Age
* Sex
* Chest Pain Type (cp)
* Resting Blood Pressure (trestbps)
* Cholesterol (chol)
* Fasting Blood Sugar (fbs)
* Resting ECG Results (restecg)
* Maximum Heart Rate Achieved (thalach)
* Exercise Induced Angina (exang)
* ST Depression (oldpeak)
* Slope of Peak Exercise ST Segment
* Number of Major Vessels (ca)
* Thalassemia (thal)
* Target Variable (Heart Disease Status)

### Target Variable

| Value | Meaning          |
| ----- | ---------------- |
| 0     | No Heart Disease |
| 1     | Heart Disease    |

---

##  Exploratory Data Analysis (EDA)

Several visualizations were created to understand the dataset:

### 1. Class Distribution

Shows the percentage of patients with and without heart disease.

### 2. Age Distribution

Analyzes how age varies among different patient groups.

### 3. Maximum Heart Rate Distribution

Examines the relationship between heart rate and heart disease.

### 4. Chest Pain Type Analysis

Shows how different chest pain categories relate to heart disease occurrence.

### 5. Cholesterol Distribution

Analyzes cholesterol levels across patient groups.

### 6. Gender Analysis

Compares heart disease occurrence between male and female patients.

Generated file:

* task3_eda.png

---

##  Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Checked dataset dimensions and data types.
3. Identified and handled missing values.
4. Removed duplicate records.
5. Standardized the target column.
6. Converted multi-class disease labels into binary classes.
7. Split data into training and testing sets.
8. Applied feature scaling using StandardScaler for Logistic Regression.

---

##  Machine Learning Models

### Logistic Regression

Logistic Regression is a linear classification algorithm that predicts the probability of heart disease occurrence.

Advantages:

* Fast training
* Interpretable results
* Suitable for binary classification

### Decision Tree Classifier

Decision Tree creates decision rules based on feature values to classify patients.

Advantages:

* Easy to interpret
* Handles nonlinear relationships
* Provides feature importance scores

---

##  Evaluation Metrics

The models were evaluated using:

### Accuracy

Measures overall prediction correctness.

### Precision

Measures how many predicted positive cases are actually positive.

### Recall

Measures how many actual positive cases are correctly identified.

### F1 Score

Harmonic mean of Precision and Recall.

### ROC-AUC Score

Measures the model's ability to distinguish between classes.

### Confusion Matrix

Provides detailed insight into classification performance.

---

##  Visualizations Generated

### Model Evaluation Dashboard

File:

* task3_model_results.png

Contains:

* Logistic Regression Confusion Matrix
* Decision Tree Confusion Matrix
* Metric Comparison Bar Chart
* ROC Curves
* Feature Importance Plot

---

### Correlation Heatmap

File:

* task3_correlation.png

Shows relationships between all dataset features.

---

### Decision Tree Visualization

File:

* task3_decision_tree.png

Displays the complete trained Decision Tree structure and decision-making process.

---

##  Project Workflow

1. Load Dataset
2. Inspect Dataset
3. Clean Data
4. Perform EDA
5. Prepare Features and Target
6. Split Training and Testing Data
7. Scale Features
8. Train Logistic Regression
9. Train Decision Tree
10. Generate Predictions
11. Evaluate Models
12. Create Visualizations
13. Compare Results
14. Identify Important Features

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

##  Results

The project successfully predicts the likelihood of heart disease using machine learning techniques and provides comprehensive visual analysis of model performance.

Model performance is evaluated through:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC
* Confusion Matrix Analysis

The comparison between Logistic Regression and Decision Tree helps identify the most effective model for heart disease classification.

---

##  Learning Outcomes

Through this project, the following concepts were explored:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Classification Algorithms
* Model Evaluation
* Data Visualization
* Healthcare Data Analytics

---

## 👨‍💻 Author
TOOBA FATIMA
Developed as part of the DevelopersHub Corporation AI Industrial Training Program (Batch 2026).

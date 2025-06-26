# Banking Credit Risk Prediction

## Overview

This project focuses on predicting banking customers' credit risk using machine learning techniques. It involves analyzing a dataset containing customer information such as income, age, credit history, and loan status. The data is preprocessed and used to train classification models that categorize customers as low-risk or high-risk. The goal is to help financial institutions make better lending decisions by accurately identifying potential credit defaults.

## Objectives

 Analyze and preprocess real-world banking customer data.
 Engineer features relevant to credit risk assessment.
 Train and evaluate classification models to predict credit risk.
 Compare performance across multiple models.
 Interpret model outputs to derive actionable insights for financial institutions.

## Project Structure

```
.
├── Banking_Credit_Risk_Project.ipynb   # Main Jupyter notebook
├── bankingdata.csv                     # Dataset used for training/testing
├── README.md                           # Project documentation
```

---

## Technologies Used

- Python 
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook
  
---
## Workflow Summary

### 1. Data Exploration and Cleaning
- Checked for null values, inconsistencies, and duplicates.
- Converted data types and cleaned formatting issues.

### 2. Exploratory Data Analysis (EDA)
- Visualized distributions and relationships between variables.
- Analyzed feature correlations.

### 3. Feature Engineering
- Encoded categorical variables.
- Scaled numerical features.
- Created derived features to enhance model input.

### 4. Model Building
- Trained classification models:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
- Used train-test split for validation.

### 5. Evaluation Metrics
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-Score
- ROC Curve and AUC

---

## Results

The model comparison identified the best-performing classifier based on the F1-score and ROC-AUC. Detailed evaluation results and insights are provided in the notebook.

## Author
Kamalika Kommineni

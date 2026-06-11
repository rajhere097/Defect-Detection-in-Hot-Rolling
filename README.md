# Defect Detection in Hot Rolling

## Project Overview
This project focuses on building an end-to-end Machine Learning pipeline for defect detection in hot rolling processes. The objective is to accurately identify defective products while minimizing missed defects and maintaining acceptable overall model performance.

## Business Problem
In manufacturing environments, undetected defects can lead to quality issues, customer dissatisfaction, and increased production costs. Therefore, the primary goal is to maximize the detection of defective products and reduce false negatives.

## Techniques Used

### Data Processing
- Data Loading
- Data Validation
- Missing Value Handling
- Correlation Analysis
- Train-Validation Split

### Feature Engineering
- Feature Selection
- Correlation-Based Analysis
- Data Preparation for Modeling

### Machine Learning Models
- Logistic Regression
- XGBoost Classifier
- Hyperparameter Tuning using RandomizedSearchCV

### Class Imbalance Handling
- class_weight='balanced'
- scale_pos_weight

### Model Evaluation
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix Analysis

### Model Deployment Preparation
- Probability-Based Predictions
- Model Serialization using Pickle (.pkl)

## Success Criteria
- Maximize Recall for Defect Class (Class 1)
- Minimize False Negatives
- Maintain acceptable Precision and Overall Model Performance
- Select the best model based on business requirements

## Final Model Selection
Logistic Regression was selected as the final model because it achieved the highest recall for defect detection (92.31%), correctly identifying 12 out of 13 defective products while missing only one defective sample.

## Results
- Recall (Defect Class): 92.31%
- Accuracy: 76.75%
- ROC-AUC: 0.88
- Defects Correctly Identified: 12/13
- Missed Defects: 1

## Project Structure
- Data Loading Pipeline
- Feature Engineering Pipeline
- Model Training Pipeline
- Model Evaluation Pipeline
- Visualization Module
- Saved Model (.pkl)

- 
**Ratnajit Chakraborty**
LinkedIn: https://www.linkedin.com/in/ratnajit-chakraborty-076ab520a

## Note
The original dataset is proprietary client data and cannot be shared publicly. Only the implementation, methodology, evaluation results, and trained model artifacts are included in this repository.

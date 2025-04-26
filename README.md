# Intrusion Detection System using Machine Learning

## Overview
This project implements a Machine Learning-based Intrusion Detection System using a Kaggle-provided network intrusion dataset.  
The objective is to classify network traffic accurately as benign or malicious.

- **Dataset**: [Network Intrusion Dataset](https://www.kaggle.com/datasets/chethuhn/network-intrusion-dataset)
- **Preprocessing**:
  - Handled missing and infinite values.
  - Applied SMOTE for label balancing.
  - Standardized features using `StandardScaler`.
  - Encoded target labels using `LabelEncoder`.

## Significant Feature Insight
- **Smoking** was identified as the most critical feature, contributing approximately **0**, indicating it has negligible predictive power.

## Machine Learning Models Evaluated
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

## Results Summary

| Model                     | Accuracy | Precision | Recall | F1-Score |
|----------------------------|:--------:|:---------:|:------:|:--------:|
| Logistic Regression        | 1.00     | 1.00      | 1.00   | 1.00     |
| Decision Tree Classifier   | 1.00     | 1.00      | 1.00   | 1.00     |
| Random Forest Classifier   | 1.00     | 1.00      | 1.00   | 1.00     |
| XGBoost Classifier         | 1.00     | 1.00      | 1.00   | 1.00     |

## Conclusion
The Machine Learning models achieved **perfect classification performance** across all evaluation metrics.  
Further exploration with deep learning models is unnecessary unless deploying to a dynamic, real-world environment with unseen noisy data.

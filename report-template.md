# Credit Risk Analysis Report

## Overview (5 points)

The purpose of this analysis is to evaluate the effectiveness of the Logistic Regression model in predicting loan statuses (healthy vs. high-risk). The analysis aims to determine whether the original dataset or a resampled dataset (to balance class sizes) would yield more accurate predictions, helping the company make informed decisions about loan approvals and risk management.

## Model Performance (5 points)

The accuracy, precision, and recall scores of the Logistic Regression model are as follows:

- **Accuracy**: 0.99
- **Precision**:
  - Class 0 (healthy loans): 1.00
  - Class 1 (high-risk loans): 0.85
- **Recall**:
  - Class 0: 0.99
  - Class 1: 0.91

## Summary and Recommendation (10 points)

The Logistic Regression model demonstrated strong overall performance, particularly in predicting healthy loans (Class 0), where both precision and recall were nearly perfect. For high-risk loans (Class 1), the model showed good recall but slightly lower precision, indicating a tendency towards false positives. 

Given the high accuracy and the balance between precision and recall, I recommend using the Logistic Regression model as a tool for predicting loan health. The model’s performance suggests it is effective at identifying both healthy and high-risk loans, which is crucial for risk management. However, to further validate the model’s reliability, I suggest testing it on different datasets to ensure its robustness across various scenarios.

If you don’t feel confident in the current model’s slight tendency towards false positives, it may be worth exploring other models or refining the Logistic Regression model to improve precision without sacrificing recall.

# Credit Risk Classification

## Overview of the Analysis

The purpose of this analysis was to develop and evaluate a machine learning model that could predict loan risk. Specifically, we aimed to identify whether a loan is likely to be "healthy" (0) or "high-risk" (

The data consisted of various financial and demographic attributes related to the loans, including loan amount, borrower credit score, and income. The target variable to predict was the loan status, where 0 indicates a healthy loan and 1 indicates a high-risk loan.

To Process data in machine learning we make this actions:
Data Preprocessing: Cleaning and preparing the dataset.
Feature Selection: Selecting the most relevant features.
Model Training: Training the logistic regression model using resampled training data.
Model Evaluation: Evaluating the model's performance using accuracy, precision, recall, and f1-score.

LogisticRegression: A logistic regression model was used to predict loan risk. The model was instantiated with solver='lbfgs' and random_state=1.

## Results:

- Machine Learning Model 1: Logistic Regression:
- Accuracy: 0.99
- Precision for class 0 (healthy loan): 1.00
- Recall for class 0: 0.99
- F1-score for class 0: 1.00
- Precision for class 1 (high-risk loan): 0.84
- Recall for class 1: 0.94
- F1-score for class 1: 0.89

## Summary

Which one seems to perform best? How do you know it performs best?
The logistic regression model performed best, achieving high accuracy and excellent precision, recall, and f1-scores for both classes.

Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the 1's, or predict the 0's?)
Performance does depend on the problem. In this case, predicting high-risk loans (class 1) is crucial to mitigate financial risk. The model showed good performance in identifying high-risk loans, with a recall of 0.94 for class 1.

Recommendation:
I recommend using the logistic regression model due to its high overall accuracy and strong performance in both identifying healthy and high-risk loans. However, continuous monitoring and tuning are suggested to maintain and potentially improve its predictive power.


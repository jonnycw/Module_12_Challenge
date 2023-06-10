# Credit Risk Analysis
## _Module 12 Challenge_

## Overview of the Analysis

The aim of the analysis was to evaluate the effectiveness of two machine learning algorithms in identifying a loan as either "healthy" or "high risk".

The data utilized in creating these two models included a sum of 77,536 instances each characterized by 7 items (loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt).

The data was divided into training and test subsets. The models deployed for this comparison were both types of logistic regression models, developed using the LogisticRegression model from Scikit-learn. One model processed the original data while the other utilized resampled data with the aid of imblearn's RandomOverSampler.

## Results

**Machine Learning Model 1:**

The model shows high accuracy when predicting the healthy loan, with a precision of 1 and a recall of 0.99. Additionally, it has a high specificity of 0.91, demonstrating a low false-positive rate.

The model shows lower accuracy when predicting a high-risk loan, as it has a precision of 0.85 and a recall of 0.91. However, it demonstrates a high specificity of 0.99, indicating a very low false-negative rate.


**Machine Learning Model 2:**

The model again shows high accuracy when prediction the healthy loan, with a precision of 1 and a recall of 0.99. As for the high-risk loan, we can see an improvement in the model. Precision dropped from 0.85 to 0.84, however, recall increased from 0.91 to 0.99. Overall, we can see that the balanced accuracy score increased significantly from 0.952 to 0.994

## Summary

Both models performed well and had similar accuracies for the "healthy" class. However, because it is more important for us to predict the "high risk" class, I recommend using the second machile learning model to take advantage of the improved accuracy.

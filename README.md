# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy: 94% 
  * Healthy Loans Precision: 100%
  * Healthy Loans Recall: 100%
  * Healthy Loans F1-Score: 100%
  * High-Risk Loans Precision: 87% 
  * High-Risk Loans Recall: 89%
  * High-Risk Loans F1-Score: 88%


* Machine Learning Model 2:
  * Accuracy: 99%
  * Healthy Loans Precision: 99%
  * Healthy Loans Recall: 99%
  * Healthy Loans F1-Score: 99%
  * High-Risk Loans Precision: 99%
  * High-Risk Loans Recall: 99%
  * High-Risk Loans F1-Score: 99%

## Summary

Both models perform nearly perfectly when predicting "Healthy" loans, but the second model is far superior at predicting "High-Risk" loans. The model produced higher precision, recall, and f1-scores for "High-Risk" loans. This model is better than Model 1, despite having worse "Healthy" loans precision, since it predicts "High-Risk" loans with far more precision than Model 1, increasing profits by reducing the number of bad loans executed.
# Module 20 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

* Explain what financial information the data was on, and what you needed to predict.
* We are predicting low and high-rik loans based on a few variables such as loan size, interest rate, borrower income, debt to income and other credit background from loaner.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* In the dataset we have 75,036 healthy loans and 2,500 high-risk loans.
* Describe the stages of the machine learning process you went through as part of this analysis.
* Data Collection, Data Preparation (split the data, logistic regression, fit the model, etc.), Data Visualization, Classification Reporting
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
* Logistic Regression Model with the Original Data, Logistic Regression Model with Resampled Training Data

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * Classification Report is showing that model has 100% precision for predicting healthy loans and 85% precision for predicting high-risk loans. Model is able to identify 99% of healthy loans and 91% of high-risk loans. Balance between the 2 previous measures (f1-score) is showing 100% for healthy loans and 88% for high-risk loans. This is a good indication about how well the model is likely to perform in real life.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  * Classification Report is showing that model has 100% precision for predicting healthy loans and 84% precision for predicting high-risk loans. Model is able to identify 99% of healthy loans and 99% of high-risk loans. Balance between the 2 previous measures (f1-score) is showing 100% for healthy loans and 91% for high-risk loans. This is a good indication that this model fit with oversampled data is likely to perform better than previous regression model in real life.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Logistic Regression Model with Resampled Training Data. It has higher precision in the high-risk loans and all that matters here is mitigate risk/loss.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
* Yes it is more important to predict the '1's

If you do not recommend any of the models, please justify your reasoning.

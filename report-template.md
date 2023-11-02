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
Model 1, The logistic regression model trained on the original data gives us a 94.4% accuracy of predicting the two labels. The model is accurate in predicting the healthy loans. The model could be iimproved as it only correctly predicted 87% of all actual high-risk loans.

Machine Learning Model 2:

Model 2 , The logistic regression model trained with the oversampled data gives a high degree of accuracy and a higher recall score giving us high confidence in the prediction. The model predicts healthy loans with a precision score of 1.00 and can predict all high-risk loans. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

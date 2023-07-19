# Credit_Risk_Classification Report 

## Overview of the Analysis
The overall project goal was to use the lending data provided to evaluate the riskiness of the loans based on logistic regression prediction models.The credit classification analysis used the following machine learning models:
First task was to read the csv lending data in to a pandas dataframe. 
Second task was to display or read the dataframe table details. 
Third task was to cerate the Y & X axis for the regression model.The Y axis was for the loan status only and the X axis for the other column excluding the loan status. A drop column formula was needed to achieve this step and re-run the pandas table without the loan status column. 
Fourth task was to use sklearn to import the train_test_split whic splits arrays or matrices into random train and test subsets of data.

## Results

* Machine Learning Model Logistic Regression:
Description of Model 1 Accuracy, Precision, and Recall scores.
The logistic regression model predicts the healthy loan (0) with 100% precision and the high risk loan (1) with 87%.
The recall scores were very similar at 100% for the healthy loan and 89% for the high risk loan.

## Summary
The logistic regression model predicts the healty loan (0) with 100% precision and the high risk loan (1) with 87%. The macro average of the precision is 94% and the  weighted average is 99% which is very good. However the lower precision score of 87% on the high-risk loan may create an undetected lending risk which will make the lending company to lose money.
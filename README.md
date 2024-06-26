# Credit Risk Classification Machine Learning Model
## Overview of the Analysis
- Purpose: To predict if the loan is healthy or high-risk by using a supervised machine learning model.
- From the data we have, based on the loan_size, interest rate, borrower income, debt to income, number of accounts, derogatory marks and total debt to predict the borrower's loan status
- Steps:
    1. Set loan_status as dependent variable (y) and the rest columns as independent variable (x).
    2. Split the data into training and testing datasets
    3. Create a Logistic Regression Model and fit the model with training data
    4. Get predictions on the testing data by using the testing data and the fitted model
    5. Evaluate the model's performance by reading the results of confusion matrix and the classification report
   
## Results
The precision rate of healthy loan is 100%
The precision rate of Non-healthy loan is 85%
The recall ratio of healthy loan is 99%
The recall ratio of Non-healthy loan is 91%
The overall accuracy rate is 99%


## Summary
The ratios are predominantly above 85%, suggesting that the model performs well.
- From the confusion matrix, we can tell that the number of True Positive and True Negative is significantly higher than the number of False Positive and False Negative. This indicates that the prediction is quite precise. 
- The number of Healthy loans is way higher than the number of Non-healthy loans leading to a discrepancy in the precision ratio between Healthy and Non-healthy loans. The model achieves 100% precision for Healthy Loans but only 85% for Non-healthy Loans.
- From recall ratio, we can see that the model can correctly capture 99% Healthy loans and 91% Non-healthy loans. This indicates that the model performs well.

# credit-risk-classification

## Overview


* The purpose of my analysis is to to train and evaluate a model based on loan risk. 
* I got a dataset with lending activity from peer to peer lending services. Based off of that data set I predict the creditworthiness of borrowers. 
* The dataset totaled 77536 entries. I set up the loan status to all other categories, (loan size, interest rate,borrower income, debt to income, number of accounts, derogatory marks, & total_debt). From there I was able to fit the data into a model that will predict the creditworthiness of each borrower. 
* I first read the data into a dataframe. I serperated the y and X , making y label the loan status and X variable all other categories. I proceededd to split the data into X_train, X_test, y_train, & y_test using train_test_split. After splitting the data and creating multiple datasets to train and test my model I fit the X_train and y_train into a logistic regression model. I was then able to use my test data to make predcitions. For the predictions i created a confusion model and classification report. 
* I used logistic regression because it will put predicted possibilities into a specific class. It alos uses multiple inputs to make its predicitons.It is fairly simple to analyze its preformance and worked well with the data provided. 

## Results

* The results of my confusion matrix showed that the logistic regression model did a good job prediciting with our data. It ouput 583 True Positives, 18655 True Negatives, and only 110 False Positives and 36 False Negatives
* The precision is %100 for the negative class and %84 for the positive class.
* The model correctly indentified %99 for the class of healthy loans and %94 for the high risk loans. 
* The classification report also showed a perfect f1-Score for the healthy loans and a good balance of .89 for the high risk. 
* the overall accuracy of the model is %99

## Summary

* Overall the model preformed well. It resulted in %99 accuracy which is good.
* Given the data provieded I would not recommend any other model, The logistic regression is prefect for making a solid "yes, 0 " or "no, 1" predicitions while factoring in multiple columns of data. 
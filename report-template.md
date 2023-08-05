# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to identify the credit-worthiness of borrowers.
* The data used was historical lending data that included loan size, interest rate, borrower income, debt to income ratio, the number of accounts, any derogatory amrks, total debt and    
the loan status.
* The purpose of the model is to predict either a healthy loan status or a high risk loan status for future borrowers.
* After pulling in the dataset and creating the labels set from the features, the data was then split into training and testing datasets.The model was then instantiated and fit using the training data. Predictions were then made on the testing data so an evaluation could be performed to determine the model's accuracy.
* LogisticRegression was used to fit the data and make predictions. Then the balanced_accuracy_score, confusion_matrix and classification_report were all used in this process.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * The balanced accuracy is a 94%
  * Healthy loan Precision is 100% while Recall is 100%
  * High-risk loan Precision is 87% while Recall is 89%



* Machine Learning Model 2:
  * Balanced accuracy is a  99%
  * Healthy loans stay at a 100% for Precision and Recall 
  * High-risk loans stay at a Precision of 87% and Recall moves up to 100% 

## Summary


* Model 2 seems to be the better model because of the higher accuracy.
* Both models need more improvment before they can become feasible. Would not recommend yet. 




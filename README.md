# Background

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Instructions
- The instructions for this Challenge are divided into the following subsections:

- Split the Data into Training and Testing Sets

- Create a Logistic Regression Model with the Original Data

- Write a Credit Risk Analysis Report

## Report: Overview of the Analysis
- Explain what financial information the data was on, and what you needed to predict.
    - The purpose of this analysis is to create and evaluate the data model that predicts the credity worthiness of potential borrorwers from peer-to-peer lending serices. The data showed financial information for each applicant and loan including: loan size, interest rate, income, debt-to-income ratio, number of accounts, any derogatory marks, and total debt.

- Provide basic information about the variables you were trying to predict.
    - The variable the model is trying to predict is the loan status, and the 2 possible outcomes are a "healthy loan" or a "high-risk loan". When looking at the breakdown of those status variables, there are more observations of healthy loans
- Describe the stages of the machine learning process you went through as part of this analysis.
    - This machine learning process started with data cleaning and some exploratory analysis to view the data being worked with, selecting the X and y features for testing, splitting test and training .datasets.
- Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
    - A RandomOverSample was used to resample the data and create an even spread between the imbalanced data set, so there were equal observations of each loan status outcome.

## Results
Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.
- Machine Learning Model 1:
    - Accuracy: 99% - 92% of predicted positives were correct
    - Precision: 92% - 92% of predicted positives were correct
    - Recall: 95% - This means that when taking into account the sensitivity (recall and/or true positive rate) and specificity (true negative rate) of the model, the balanced prediction accuracy was 95%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any.
- Both models really performed well with 90%+ accuracy.

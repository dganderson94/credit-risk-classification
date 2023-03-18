# Credit Risk Analysis Report

## Overview

The purpose of this analysis is to determine which of two machine learning models is able to more effectively predict whether loans will be healthy or high-risk. Predictions are based on loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and total debt. The two models both used logistic regression to make their predictions, with the second model employing random oversampling to adjust the class distribution.

## Results

* Machine Learning Model 1:
  * Accuracy: 99%
  * Precision:
    * Healthy Loans: 99%
    * High-Risk Loans: 91%
    * Macro Average: 95%
    * Weighted Average: 99%
  * Recall:
    * Healthy Loans: 100%
    * High-Risk Loans: 85%
    * Macro Average: 92%
    * Weighted Average: 99%

<br>

* Machine Learning Model 2:
  * Accuracy: 99%
  * Precision:
    * Healthy Loans: 99%
    * High-Risk Loans: 99%
    * Macro Average: 99%
    * Weighted Average: 99%
  * Recall:
    * Healthy Loans: 100%
    * High-Risk Loans: 84%
    * Macro Average: 92%
    * Weighted Average: 99%

## Summary

Both models scored admirably, with each only dipping below 90% with regards to recall on high-risk loans. Model 2 perfomed slightly better, with a 4% increase in macro average precision over Model 1. It is worth mentioning, however, that Model 1 had 1% higher recall on high-risk loans than Model 2.

Overall, while I can certainly recommend either model, Model 2—the one that used random oversampling—has a slight edge, compared to Model 1.
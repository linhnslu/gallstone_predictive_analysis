## Project Overview

This project develops machine learning models to predict gallstone disease using clinical, laboratory, and bioimpedance data from the UCI Gallstone dataset. 
The goal is to evaluate multiple classification techniques and identify the most accurate and clinically interpretable model for early risk stratification.

## Language & Tools

+ Language: R

+ Frameworks/Libraries: caret, tidyverse, ggplot2, pROC, randomForest, gbm, e1071

## Models Evaluated

The following predictive models were trained and compared using repeated 10-fold cross-validation and an independent holdout test set:

+ Logistic Regression with Lasso Regularization

+ Linear Discriminant Analysis (LDA)

+ Quadratic Discriminant Analysis (QDA)

+ K-Nearest Neighbors (KNN)

+ Random Forest

+ Gradient Boosting Machine (GBM)

+ Support Vector Machines (Linear & Radial)

## Best Performing Model

The Logistic Regression model achieved the strongest validation performance on the holdout set, with:

ROC (AUC): 0.907

Accuracy: 0.841

Sensitivity: 0.875

Specificity: 0.806

## Conclusion & Clinical Relevance

Logistic Regression performed as well as and in some cases better than more complex models while remaining fully interpretable. 
Key predictors included C-reactive protein (CRP), vitamin D, hepatic fat accumulation, and body-composition markers. 
Clinically, these findings support the use of simple, transparent models to enhance early detection and guide pre-imaging risk assessment for patients with potential gallstone disease.

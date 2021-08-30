# Credit_Risk_Analysis
Module 17: Supervised Machine Learning and Credit Risk

## **Overview of the Analysis**

The purpose of the Credit Risk Analysis perfomred was to create machine learning algorithms to train and test various models such as; Naive Random Oversampling, SMOTE Oversampling, Undersampling, Combination (Over and Under) Sampling, Balanced Random Forest Classifier, and Easy Ensemble AdaBoost Classifier, to aide in the classification of risky loans. Through training and testing groups of a given data set, the objective is to determine which supervised learning algorithm will yield the best performance.

## Results

The six supervised machine learning models including their respective balanced accuracy, precision, and recall scores, are as follows:

#### Naive Random Oversampling

- Balanced Accuracy: 0.67986
- Precision: The precision is 0.01 for high risk loans and is 1.00 for low risk loans
- Recall: The recall is 0.59 for high risk loans and is 0.68 for low risk loans

![Naive Random Oversampling](https://github.com/sqrtofpi/Credit_Risk_Analysis/blob/e05aaf998ec6ffa31b59dd0c1887c2fe5667347a/Resources/Naive%20Random%20Oversampling.png)

#### SMOTE Oversampling

- Balanced Accuracy: 0.64435
- Precision: The precision is 0.01 for high risk loans and is 1.00 for low risk loans
- Recall: The recall is 0.61 for high risk loans and is 0.64 for low risk loans

![SMOTE Oversampling](https://github.com/sqrtofpi/Credit_Risk_Analysis/blob/e05aaf998ec6ffa31b59dd0c1887c2fe5667347a/Resources/SMOTE%20Oversampling.png)

#### Undersampling

- Balanced Accuracy: 0.43110
- Precision: The precision is 0.01 for high risk loans and is 1.00 for low risk loans
- Recall: The recall is 0.60 for high risk loans and is 0.43 for low risk loans

![Undersampling](https://github.com/sqrtofpi/Credit_Risk_Analysis/blob/e05aaf998ec6ffa31b59dd0c1887c2fe5667347a/Resources/Undersampling.png)

#### Combination (Over and Under) Sampling

- Balanced Accuracy: 0.54287
- Precision: The precision is 0.01 for high risk loans and is 1.00 for low risk loans
- Recall: The recall is 0.71 for high risk loans and is 0.54 for low risk loans

![Combination (Over and Under) Sampling](https://github.com/sqrtofpi/Credit_Risk_Analysis/blob/e05aaf998ec6ffa31b59dd0c1887c2fe5667347a/Resources/Combination%20(Over%20and%20Under)%20Sampling.png)

#### Balanced Random Forest Classifier

- Balanced Accuracy: 0.90764
- Precision: The precision is 0.04 for high risk loans and is 1.00 for low risk loans
- Recall: The recall is 0.67 for high risk loans and is 0.91 for low risk loans

![Balanced Random Forest Classifier](https://github.com/sqrtofpi/Credit_Risk_Analysis/blob/e05aaf998ec6ffa31b59dd0c1887c2fe5667347a/Resources/Balanced%20Random%20Forest%20Classifier.png)

#### Easy Ensemble AdaBoost Classifier

- Balanced Accuracy: 0.94281
- Precision: The precision is 0.07 for high risk loans and is 1.00 for low risk loans
- Recall: The recall is 0.90 for high risk loans and is 0.94 for low risk loans

![Easy Ensemble AdaBoost Classifier](https://github.com/sqrtofpi/Credit_Risk_Analysis/blob/e05aaf998ec6ffa31b59dd0c1887c2fe5667347a/Resources/Easy%20Ensemble%20AdaBoost%20Classifier.png)

## Summary

Interpreting the results of the analysis we understand that balanced accuracy we are looking for a value as close to possible to a value of 1, which in our analysis was the result of the Easy Ensemble AdaBoost Classifier model at 0.94281. The precision was nearly indistinguishable from model to model with the Easy Ensemble AdaBoost Classifier only slightly better. The recall performance was again better with the Easy Ensemble AdaBoost Classifier model and this is the model we can conclude will yield the best results with datasets containing similar data to assess Credit Risk.

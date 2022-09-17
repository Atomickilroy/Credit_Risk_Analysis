# Credit_Risk_Analysis

## Overview of Project

#### - *Using a credit card credit dataset from LendingClub, a peer-to-peer lending services company, the goal was to oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then use the SMOTEENN algorithm, an over and undersampling technique. Lastly use two new Ensemble Learners machine learning models that reduce bias, BalancedRandomForestClassifier, AdaBoostClassifier, to predict credit risk.*

![mobile](https://github.com/Atomickilroy/Credit_Risk_Analysis/blob/main/png/Screenshot%202022-09-17%20124821.png) 


## Purpose

**The purpose of this project was to start learning tools that work hand and hand web visulatizations:**
    - Explain how a machine learning algorithm is used in data analytics.
    - Create training and test groups from a given data set.
    - Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
    - Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
    - Compare the advantages and disadvantages of each supervised learning algorithm.
    - Determine which supervised learning algorithm is best used for a given data set or scenario.
    - Use ensemble and resampling techniques to improve model performance.

## Results:  

### Random Oversampling:
![map](https://github.com/Atomickilroy/Credit_Risk_Analysis/blob/main/png/Random%20Oversampling.png)

From the Random Oversampling:

Precision, reliablitiy of possitive classifitcation, is low (0.01) for predicting high credit risk .
The recall,  ability to classify, is low(0.63) for pridicting high credit risk. 
The F1 score, the weighted true-positives rate is for prdicting risk(0.02).

### SMOTE Oversampling:
![mobile](https://github.com/Atomickilroy/Credit_Risk_Analysis/blob/main/png/SMOTE%20Oversampling.png) 

From the SMOTE Oversampling:

Precision, reliablitiy of possitive classifitcation, for predicting high credit risk is low (0.01).
The recall,  ability to classify, is low(0.62) for pridicting high credit risk. 
The F1 score, the weighted true-positives rate is for prdicting risk(0.02).

### RandomUnderSampler:
![map](https://github.com/Atomickilroy/Credit_Risk_Analysis/blob/main/png/Resample%20the%20data%20using%20the%20ClusterCentroids%20resampler.png)

From the SMOTE Oversampling:

Precision, reliablitiy of possitive classifitcation, for predicting high credit risk is low (0.01).
The recall,  ability to classify, is low(0.63) for pridicting high credit risk. 
The F1 score, the weighted true-positives rate is for prdicting risk(0.02).

### SMOTEENN:
![mobile](https://github.com/Atomickilroy/Credit_Risk_Analysis/blob/main/png/Combination%20(Over%20and%20Under)%20Sampling.png)

From the SMOTEENN Over/Under Sampling:

Precision, reliablitiy of possitive classifitcation, for predicting high credit risk is low (0.01).
The recall,  ability to classify, is low(0.72) for pridicting high credit risk. 
The F1 score, the weighted true-positives rate is for prdicting risk(0.02).

### BalancedRandomForestClassifier:
![mobile](https://github.com/Atomickilroy/Credit_Risk_Analysis/blob/main/png/Balanced%20Random%20Forest%20Classifier.png) 

From the BalancedRandomForestClassifier:

Precision, reliablitiy of possitive classifitcation, for predicting high credit risk is low (0.04).
The recall,  ability to classify, is low(0.67) for pridicting high credit risk. 
The F1 score, the weighted true-positives rate is for prdicting risk(0.07).

### Ensemble AdaBoost Classifier:
![mobile](https://github.com/Atomickilroy/Credit_Risk_Analysis/blob/main/png/Ensemble%20AdaBoost%20Classifier.png)

From the Ensemble AdaBoost Classifier:

Precision, reliablitiy of possitive classifitcation, for predicting high credit risk is low (0.85).
The recall,  ability to classify, is low(0.38) for pridicting high credit risk. 
The F1 score, the weighted true-positives rate is for prdicting risk(0.52).


## Conclusion

From the confusion matries' results from the 6 machine learning models, the precision for the identifying  <br>
high risk across all models to low to be considered a strong and reliable model. Despite an increase in the 
precision the model needs additional iterations.

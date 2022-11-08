# Credit_Risk_Analysis

Supervised Machine Learning and Credit Risk



## Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. In this project different techniques were used to train and evaluate models with unbalanced classes. Utilizing various libraries and algorithms to build and evaluate models using resampling including:

   imbalanced-learn
   
   scikit-learn
   
   RandomOverSampler
   
   SMOTE algorithms
   
   ClusterCentroids algorithm
   
   SMOTEENN algorithm
   
   BalancedRandomForestClassifier (bias reduction model)
   
   EasyEnsembleClassifier (bias reduction model)
   
   

## Purpose

The purpose of the project is to explain how a machine learning algorithm is used in data analytics. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company We created training and test groups from a given data set. Implement the logistic regression, decision tree, random forest, and support vector machine algorithms. Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms. As well as compare the advantages and disadvantages of each supervised learning algorithms. We determine which supervised learning algorithm is best used for a given data set or scenario. Use ensemble and resampling techniques to improve model performances.



## Results
 
    
The results for the six machine learning models including their respective balanced accuracy, precision, and recall scores are as follows:

## Naive Random Oversampling

<img width="770" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/90155651/200503469-c73ddd25-c4c4-4ae1-8c74-41611c4dc6c7.png">


1. Balanced Accuracy: 0.6742571941946299
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .74/.61


## SMOTE Oversampling

<img width="744" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/90155651/200505650-b0458807-566a-48ad-a34f-8364b57a01c2.png">

1. Balanced Accuracy: 0.5447339051023905
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .63/.69



## Undersampling

<img width="720" alt="# Undersampling" src="https://user-images.githubusercontent.com/90155651/200505823-ce59ee8f-a64f-478e-88c5-39d6cc428846.png">

1. Balanced Accuracy: 0.6623356588465208
2. Precision: The precision is low for High-risk loans and is low for Low-risk loans.
3. Recall: High/Low risk = .69/.40


## Combination Under-Over Sampling

<img width="731" alt="# Combination (Over and Under) Sampling" src="https://user-images.githubusercontent.com/90155651/200505937-979f9989-f277-46f0-829a-34d37346e34d.png">

1. Balanced Accuracy: 0.6447701423556762
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .72/.69


## Balanced Random Forest Classifier

<img width="724" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/90155651/200509116-5df67f2c-613d-4aeb-a8b8-5886aaa58f57.png">


. Balanced Accuracy: 0.7885466545953005
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .70/.87



## Easy Ensemble AdaBoost Classifier

<img width="747" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/90155651/200510439-35fc2af9-a318-4506-b8d4-b8c7ae67ce18.png">


. Balanced Accuracy: 0.9316600714093861
2. Precision: The precision is low for High-risk loans and is high for Low-risk loans.
3. Recall: High/Low risk = .92/.94


## Summary


When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.

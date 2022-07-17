# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to design and assess the efficacy of machine learning when assigned to a dataset of credit data. The ultimate goal of this exploration is to create a supervised machine learning algorithm that can accurately predict and analyze credit risk based on previous data.

## Results

* ### RandomOverSampler
![RandomOverSampler Results](/Resources/RandomOverSampling.png)

The Balanced Accuracy of this model is approximately 65.57%. Precision: (High Risk) = 0.01, (Low Risk) = 1.00. Recall: (High Risk) = 0.72, (Low Risk) = 0.59. 


* ### SMOTE
![SMOTE Oversampling Results](/Resources/SMOTEOversampling.png)

The Balanced Accuracy of this model is approximately 66.2%. Precision: (High Risk) = 0.01, (Low Risk) = .99 . Recall: (High Risk) = 0.63, (Low Risk) = 0.69.  


* ### UnderSampling
![Undersampling Results](/Resources/Undersampling.png)

The Balanced Accuracy of this model is approximately 54.42%. Precision: (High Risk) = 0.01, (Low Risk) = .99 . Recall: (High Risk) = 0.69, (Low Risk) = 0.40.  

* ### SMOTEENN - Combination Under and OverSampling
![SMOTEENN Results](/Resources/SMOTEENN.png)

The Balanced Accuracy of this model is approximately 64.13%. Precision: (High Risk) = 0.01, (Low Risk) = .99 . Recall: (High Risk) = 0.71, (Low Risk) = 0.57.  


* ### Balanced Random Forest Classifier
![Balanced Random Forest Classifier Results](/Resources/BalancedRandomForest.png)

The Balanced Accuracy of this model is approximately 78.85%. Precision: (High Risk) = 0.04, (Low Risk) = 1.00 . Recall: (High Risk) = 0.70, (Low Risk) = 0.87.  

* ### EasyEnsemble AdaBoost Classifier
![EasyEnsemble Error](/Resources/EasyEnsembleError.png)

I was unable to calculate the Balanced Accuracy, Recall, and Precision Statistics as I has this reoccuring error. For the time being I decided to move forward with the results I was able to analyze and hope to debug this portion of the code at a later date. 

## Summary
I was unable to accurately compare all of the models due to my error with the EasyEnsemble AdaBoost Classifier. Therefore, I am unable to make a clear consensus on the best avenue for accuracy until I am able to debug my code for that portion of the data. 

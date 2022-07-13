# Credit_Risk_Analysis
Using supervised machine learning to analyze credit risk

## Overview
A lending service tasked me with determining the credit risk of loans using multiple machine learning models. Using Random Oversampling, SMOTE, Cluster Centroids, SMOTEENN, Balanced Random Forest Classifier, and Easy Ensemble Classifier, on the same test data and under the same conditions I was able to compare the results of the machine learning models. 

## Results
RandomOverSampler:
![RandomOverSample](https://user-images.githubusercontent.com/99688417/178790893-8b2bb287-acc7-425b-8210-99a8f493659a.png)



SMOTE:
![smote](https://user-images.githubusercontent.com/99688417/178790921-a509c6d2-c1ec-4206-b6dd-1f05b593128e.png)

Cluster Centroid:
![Undersample](https://user-images.githubusercontent.com/99688417/178792141-451aec92-0beb-4521-97be-e41cd26326df.png)


SMOTEENN:
![overundersample](https://user-images.githubusercontent.com/99688417/178791966-7166d755-f918-4837-b5eb-b4f52be7304c.png)

BalancedRandomForestClassifier:
![Random forest](https://user-images.githubusercontent.com/99688417/178791913-a41ddf32-8c7d-4968-bc98-2338986dd9c2.png)


EasyEnsembleClassifer:
![Ensemble](https://user-images.githubusercontent.com/99688417/178791011-40d02458-7d11-49e9-be4f-4240227732a0.png)



## Summary
In summation, after analyzing the machine learning models it is clear that the better model to use for accurate credit risk predictions is the Easy Ensemble Ada boost classifier as it produced the most accurate response and the balanced accuracy score is the closest to 1. 

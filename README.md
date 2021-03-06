# Credit_Risk_Analysis
## Overview of the loan prediction risk analysis
The purpose of this analysis was to evaluate different classification models for predicting credit risk.
## Results
* RandomOverSampler
  * Accuracy: 0.64
  * ![RandomOverSampler](Images/RandomOverSampler.png)
* SMOTE
  * Accuracy: 0.67
  * ![SMOTE](Images/SMOTE.png)
* ClusterCentroids
  * Accuracy: 0.40
  * ![ClusterCentroids](Images/ClusterCentroids.png)
* SMOTEENN
  * Accuracy: 0.56
  * ![SMOTEENN](Images/SMOTEENN.png)
* BalancedRandomForrestClassifier
  * Accuracy: 0.999
  * ![BalancedForestClassifer](Images/BalancedForestClassifer.png)
* EasyEnsembleClassifier
  * Accuracy: 1.0
  * ![EasyEnsembleClassifier](Images/EasyEnsembleClassifier.png)
## Summary
Based on the results that I got, I would recommend using either the BalancedRandomForrestClassifier or the EasyEnsembleClassifier. The reason being that they were almost identical in accuracy, precision, and recall, but were higher in all three than the other classifiers.

# Credit_Risk_Analysis

## Overview
Using the credit card credit dataset from LendingClub, compare oversampling, undersampling, combinatorial, and 2 new machine learning models.

## Results
### Oversampling Algorithms
#### Native Random Oversampling
-Balance Accuracy Score: 63%<br />
-Confusion Matrix:
&nbsp;| Predicted True | Predicted False
| :--- | :---: | :---:
Actually True  | 66 | 35
Actual 1 | 6691 | 10413

-Classification Report
![Classification Report](https://github.com/Lindsey-Maag/Credit_Risk_Analysis/blob/main/images/ros.PNG)

#### SMOTE
-Balance Accuracy Score: 66%<br />
-Confusion Matrix:<br />
&nbsp;| Predicted True | Predicted False
| :--- | :---: | :---:
Actually True  | 64 | 37
Actually False | 5272 | 11832

-Classification Report
![Classification Report](https://github.com/Lindsey-Maag/Credit_Risk_Analysis/blob/main/images/smote.PNG)

### Undersampling Algorithms
#### ClusterCentroids
-Balance Accuracy Score: 54%<br />
-Confusion Matrix:<br />
&nbsp;| Predicted True | Predicted False
| :--- | :---: | :---:
Actually True  | 70 | 31
Actually False | 10340 | 6764

-Classification Report
![Classification Report](https://github.com/Lindsey-Maag/Credit_Risk_Analysis/blob/main/images/cc.PNG)
 
### Combination  Algorithm
#### SMOTEENN
-Balance Accuracy Score: 66%<br />
-Confusion Matrix:<br />
&nbsp;| Predicted True | Predicted False
| :--- | :---: | :---:
Actually True  | 79 | 22
Actually False | 7823 | 9281

-Classification Report
![Classification Report](https://github.com/Lindsey-Maag/Credit_Risk_Analysis/blob/main/images/smoteenn.PNG)
 
### New Models
#### Balanced Random Forest Classifier
-Balance Accuracy Score: 79%<br />
-Confusion Matrix:<br />
&nbsp;| Predicted True | Predicted False
| :--- | :---: | :---:
Actually True  | 71 | 30
Actually False | 2145 | 14958

-Classification Report
![Classification Report](https://github.com/Lindsey-Maag/Credit_Risk_Analysis/blob/main/images/brf.PNG) 

#### Easy Ensemble AdaBoost Classifier
-Balance Accuracy Score: 93%<br />
-Confusion Matrix:<br />
&nbsp;| Predicted True | Predicted False
| :--- | :---: | :---:
Actually True  | 93 | 38
Actually False | 985 | 15119

-Classification Report
![Classification Report](https://github.com/Lindsey-Maag/Credit_Risk_Analysis/blob/main/images/cc.PNG)

## Summary
The Easy Ensemble AdaBoost Classifer as the highest balance accuracy score of 93%. However, it still predicted 985 false positives as the precision high-risk value is only 0.09. I would recommend using a different machine learning model to determine credit risk as the above models are not sensitive enough to predict high risk loans with much clarity.

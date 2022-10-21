# Credit_Risk_Analysis

## Overview

## Results
### Oversampling Algorithms
#### Native Random Oversampling
-Balance Accuracy Score: 63%<br />
-Confusion Matrix:<br />
CM | Predicted 0| Predicted 1
| :--- | :---: | :---:
Actual 0  | 66 | 35
Actual 1 | 6691 | 10413
-Classification Report
![Classification Report](https://github.com/Lindsey-Maag/Credit_Risk_Analysis/blob/main/images/ros.PNG)

#### SMOTE
-Balance Accuracy Score: 66%<br />
-Confusion Matrix:<br />
[[   64,    37],<br />
 [ 5272, 11832]]<br />
-Classification Report
![Classification Report](https://github.com/Lindsey-Maag/Credit_Risk_Analysis/blob/main/images/smote.PNG)

### Undersampling Algorithms
#### ClusterCentroids
-Balance Accuracy Score: 54%<br />
-Confusion Matrix:<br />
[[   70,    31],<br />
 [10340,  6764]]<br />
-Classification Report
![Classification Report](https://github.com/Lindsey-Maag/Credit_Risk_Analysis/blob/main/images/cc.PNG)
 
### Combination  Algorithm
#### SMOTEENN
-Balance Accuracy Score: 66%<br />
-Confusion Matrix:<br />
[[   79,    22],<br />
 [ 7823,  9281]]<br />
-Classification Report
![Classification Report](https://github.com/Lindsey-Maag/Credit_Risk_Analysis/blob/main/images/smoteenn.PNG)
 
### New Models
#### Balanced Random Forest Classifier
-Balance Accuracy Score: 79%<br />
-Confusion Matrix:<br />
[[   71,    30],<br />
 [ 2145, 14958]]<br />
-Classification Report
![Classification Report](https://github.com/Lindsey-Maag/Credit_Risk_Analysis/blob/main/images/brf.PNG) 

#### Easy Ensemble AdaBoost Classifier
-Balance Accuracy Score: 93%<br />
-Confusion Matrix:<br />
[[   93,     8],<br />
 [  985, 15119]]<br />
-Classification Report
![Classification Report](https://github.com/Lindsey-Maag/Credit_Risk_Analysis/blob/main/images/cc.PNG)

## Summary

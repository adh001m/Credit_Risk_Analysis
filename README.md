# Credit_Risk_Analysis
## Overview
####
  In this project, supervised machine-learning was utilized to analyze credit risk. The purpose of this challenge was to familiarize oneself with supervised machine learning using imbalanced-learn and scikit-learn libraries to build models and evalute them using a resampling method. In the beginning models, I oversampled data using the randomoversampler and SMOTE algorithms, meanwhile, similiarly enough; I undersampled data using the clustercentroid algorithm. Throughout the remaining models I used a combination approach to over/under-sample the data using SMOTEENN. Finally, I compared two machine learning models that minimize bias, THE balancedrandomforestclassifier and easyensembleclassifier.
.
## Results
### Naive Random Oversampling results: 
####
Our balanced accuracy test it 64.3%, the precision for the high-risk has a very low positivity at 1% and a recall of 69%

### SMOTE oversampling results: 
####
The accuracy score is 66.2%, the precision for the high-risk loans has a low positvity again at 1% and recall is 69% overall smote or 63% for hisk-risk loans

### Undersampling results: 
####
Balanced accuracy score is 66.2% overall, with a precision of 99% overall or 1% for high-risk loans. Furthermore, we have a recall of 40% overall or 69% for high risk loans

### Combination(over and undersampling) results:
####
Balanced accuracy score is 54.4% with a precision of 99% overall and recall of 57% overall.

### Balanced Random Forest Classifier results:
#### 
The accuracy score is 77%, precision is 99% overall with a recall of 90% overall
### Easy Ensemble AdaBoost Classifier results: 
####
The accuracy score is 91.7%, the precision of 99% and a recall is 94% overall

## Analysis

####
  Throughout the first four models, I undersampled, oversampled, and did a combination of both to try and determine which model is best and most effecient at predicting high-risk loans. Throughout the following two models, I resampled the data using ensemble classifiers to try and predict which which loans are high or low risk. The accuracy score of our first four models doesn't compare to the results using ensemble classifiers. Hisk-risk loans held both a low precison and recall score in our oversampling/undersampling/mixed models. An effective models should include a high recall and precision which score, therefore; I recommend utilizing ensemble classifiers for loan classifcations over sampling techinques such as SMOTE or SMOTEENN.

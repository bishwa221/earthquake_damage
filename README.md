# Earthquake Prediction Using Machine Learning
Prediction of damage incurred by buildings due to 2015 Earthquake in Nepal.

A machine learning project that provides a damage prediction with accuracy of 74.8%.
The damages are discretized into three class, in the raw data itself.

The processes involved are:

- Exploratory data analysis.
- Data preprocessing (One-hot encoding, binning, feature engineering and feature selection)
- Preliminary run with Singular Value Decomposition(SVD).
- Training with different classifiers (SVC, KNN, Decision, Random Forest, LightBGM, XGBoost, Naive Bayes, Bagging).
- Tuning with Random Search  (Grid Search was considered but was dropped due to limited time. Could be considered as a possible way for potential improvement)
   
The data was collected through surveys by Kathmandu Living Labs and the Central Bureau of Statistics, which works under the National Planning Commission Secretariat of Nepal. This survey is one of the largest post-disaster datasets ever collected, containing valuable information on earthquake impacts, household conditions, and socio-economic-demographic statistics.

This model was able to achieve micro-average F1 score of 0.7416 when tested on drivendata.org (Richter's Predictor: Modeling Earthquake Damage competition).
It secured rank of #869 out of 6700. 


![richter](https://github.com/bishwa221/earthquake_prediction_ML/assets/94813630/11e08ac3-e43b-4f15-acfa-ec165aa21a02)


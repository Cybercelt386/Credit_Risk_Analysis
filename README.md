# Credit_Risk_Analysis

## Overview
The purpouse of this Analysis was to determine the risk of a credit accout going into default based on various data regarding the account. To acheive this I employed structured machine learning, however the data set was imbalanced. To correct this imbalance I ran three different resampling techniquies oversampling, undersampling, and over under sampling. once the imballance had beeen accounted for I applied Randomforest and EasyEnsemble to generate the risk of an account going into default. 

## Results

* The ballaced acuraccy scores are:
0.6632644555381637 (naive random oversampling)


![1](https://user-images.githubusercontent.com/111584967/220498944-1d5068a2-969e-4d4a-a5fb-ed6f1c5c7d2d.PNG)



0.6503793913067639 (SMOTE oversampling)


![2](https://user-images.githubusercontent.com/111584967/220498974-337985aa-f778-44fa-89b8-9dd649402a97.PNG)



0.6503793913067639 (Cluster Centroids undersampling)


![3](https://user-images.githubusercontent.com/111584967/220498991-dfe14720-8484-4fb6-ae08-9f848d5cac7a.PNG)



0.5436713894729043 (SMOTEEN combination sampling)


![4](https://user-images.githubusercontent.com/111584967/220499024-831dbb2e-dce1-4f67-9a6b-97f103d369b5.PNG)



1.0 (Balanced Random Forest)


![5](https://user-images.githubusercontent.com/111584967/220499046-9fe34698-1bcf-4e15-9704-fe8f7e52366d.PNG)



1.0 (Easy Ensemble AdaBoost Classifier)


![5](https://user-images.githubusercontent.com/111584967/220499068-dfc3502d-6823-4ca6-bd68-cf3d621f3abd.PNG)




* by fitting our model using resampled data I was able to accuratly predit the risk catagory of an account. with a pecision and recall score of 1.00
* 


![Capture](https://user-images.githubusercontent.com/111584967/220496786-47fd4152-653b-42a0-bdc9-abfc2dcee552.PNG)




## Summary and conclusion

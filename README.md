# Credit_Risk_Analysis

## OVERVIEW OF THE ANALYSIS
The purpose of this analysis is to create supervised machine learning models to predict loan status for customers base on some input variables. In this analysis, we use Random Oversampling, SMOTE Algorithm Oversampling, Cluster Centroid Undersampling, SMOTEENN, Balanced Random Forest Classifying, Easy Ensemble Classifying. In these machine learning models, we split the data into training and testing to get the accuracy scores, confusion matrix and classification reports to see which machine learning model does the best prediction. 

## Results

1. Raive Random Oversampling
<img width="706" alt="Oversampling" src="https://user-images.githubusercontent.com/92563285/155581588-f3745e1d-4459-476c-ab65-06c8cad7a55d.png">

2. SMOTE Oversampling
<img width="697" alt="SMOTE" src="https://user-images.githubusercontent.com/92563285/155581923-61f77830-373b-46ac-8d36-2382617c4bd5.png">

3. Clsuter Centroid Undersampling
<img width="700" alt="Undersampling" src="https://user-images.githubusercontent.com/92563285/155581962-851158fb-7c0a-4b91-bb9b-e55e69e7b7af.png">

4. SMOTEEN Sampling
<img width="697" alt="SMOTE" src="https://user-images.githubusercontent.com/92563285/155582005-c63934b2-af28-4897-bd49-d9ecd69b607e.png">


5. Balanced Random Forest Classifying
<img width="687" alt="BALANCEDRANDOMFOREST" src="https://user-images.githubusercontent.com/92563285/155582032-f157b6c3-64fe-44b3-af05-2ceacf1b4896.png">


6. Easy Ensemble Classifying
<img width="677" alt="EASYENSAMBLECLASSIFIER" src="https://user-images.githubusercontent.com/92563285/155582055-9a060d8f-270a-442b-b79c-14eecbef3d20.png">

## Summary
This analysis is to see which model can detect loan status with high risk accurately which means we should look at the recall rates and accuracy scores from these models. 

#### Accuracy Scores
1. Random Oversampling : 65%
2. SMOTE : 66%
3. Undersampeling : 54%
4. SMOTEENN : 65%
5. Balanced Random Forest Classifying : 79%
6. Easy Ensemble Classifier : 93%

#### Recall Scores for High Risk
1. Random Oversampling : 72%
2. SMOTE : 63%
3. Undersampeling : 69%
4. SMOTEENN : 72%
5. Balanced Random Forest Classifying : 70%
6. Easy Ensemble Classifier : 92%

After comparing all the learning machine model scores, we would recommend using the Easy Ensemble Classifying model to predict the high risk loan status for this analysis.







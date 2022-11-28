# 10Year_CardioVascular_Risk_Prediction
Problem Statement: 

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD). The dataset provides the patients’ information. It includes over 4,000 records and 15 attributes.

Goal: 

Predict whether a patient should be diagnosed with Heart Disease. This is a binary outcome.  1, a patient diagnosed with Heart Disease. 0, a patient not diagnosed with Heart Disease. Experiment with various Classification Models & see which yields the greatest accuracy. Examine trends & correlations within our data Determine which features are most important to Positive/Negative Heart Disease diagnosis.

Solution Approach: 

After importing the dataset, Initially, we did data preprocessing, handling nan values and outliers detection. Then we did some data analysis like we divide gender into age groups. Then explore the total number of current smokers in every age group. 
After that, we visualize how the medical (history) factors like BPMeds, Prevalent Stroke, Prevalent Hypertensive, and Diabetes and medical(current) factors like total cholesterol, Systolic Blood Pressure, Diastolic Blood Pressure, BMI, Heart Rate, and Glucose varies through age group.
The correlation matrix is used for attribute selection for this model. Then we did preprocess again like transforming data into our required format, using SMOTE for dealing with imbalanced data sets. We split the dataset into training and testing data. 
This study compares the accuracy score of Logistic Regression, K-Nearest Neighbour, Decision Tree, Random Forest, Gradient Boosting, LightGradient Boosting, Extreme Gradient Boosting, AdaBoost, CatBoost, and Gaussian Naive Bayes classifiers with algorithm GridSearchCV and RandomizedSearchCV for predicting heart disease.

Conclusion: 

With the increasing number of deaths due to heart diseases, it has become mandatory to develop a system to predict heart diseases effectively and accurately. The motivation for the study was to find the most efficient ML algorithm for the detection of heart diseases. The result of this study indicates that the Random Forest algorithm is the most efficient algorithm with an accuracy score of 89% for the prediction of heart disease. In the future, the work can be enhanced by developing a web application based on the Gradient Boosting algorithm as well as using a larger dataset as compared to the one used in this analysis which will help to provide better results and help health professionals in predicting the heart disease effectively and efficiently.

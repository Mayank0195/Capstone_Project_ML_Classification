# Capstone_Project_ML_Classification_Cardiovascular_Risk_Prediction

# Problem Description
Visiting hospitals for regular check-ups it is almost always seen that they encourage people to get special check-ups to identify if they are at risk of heart diseases. Heart diseases have unfortunately become very common. It may be due to various reasons such as lifestyle, work pressure, lack of exercise, etc. 

In this project, we will be working on predicting the 10-year risk of Coronary Heart Disease (CHD). We are given a set of variables that impact heart diseases. These variables are related to demographic, past, and current medical history.

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham,
Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of
future coronary heart disease (CHD). The dataset provides the patients’ information. 

It includes over 4,000 records and 15 attributes.
Variables.

Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk
factors.

# Data Description

data_cardiovascular_risk - historical data including Sales


This shows an overview of the Columns, non-null count and the data types of the dataset

# Attributes:

**sex:** male(0) or female(1);(Nominal)

**age:** age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous)

**is _smoking:** whether or not the patient is a current smoker (Nominal)

**cigsPerDay:** the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.)

**BPMeds:** whether or not the patient was on blood pressure medication (Nominal)

**prevalentStroke:** whether or not the patient had previously had a stroke (Nominal)

**prevalentHyp:** whether or not the patient was hypertensive (Nominal)

**diabetes:** whether or not the patient had diabetes (Nominal)

**totChol:** total cholesterol level (Continuous)

**sysBP:** systolic blood pressure (Continuous)

**diaBP:** diastolic blood pressure (Continuous)

**BMI:** Body Mass Index (Continuous)

**heartRate:** heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of a large number of possible values.)

**glucose**: glucose level (Continuous)

10 year risk of coronary heart disease CHD (binary: “1” means “Yes”, “0” means “No”) - Target Variable


# Approach 

The following approach was followed in the completion of the project:
1. Business Problem
2. Data Collection and Preprocessing
   - Data Cleaning
   -Missing Data Handling
3. Exploratory Data Analysis
    - Univariate Analysis
    -Bivariate Analysis
    -Multivariate Analysis
4. Data Manipulation
   -Outlier Detection and Treatment
   -Feature Engineering
5. Modeling
   -Sampling
   -Feature Scaling
   -Train Test Split
   -Baseline Model 
   -Confusion Matrix and Feature Importance
6. Model Performance and Evaluation
   -Comparison among the models
7. Conclusion.


# Conclusion And Recommendation

## Conclusion

Some Important conclusion drawn from the analysis are as follow:
 
•	The Target Value distribution is highly imbalanced. As in, the number of negative cases outweighs the number of positive cases. This would lead to a class imbalance problem while fitting our models. Therefore, this problem needs to be addressed and taken care of.

•	According to this dataset, males have shown a slightly higher risk of coronary heart disease Ten Year CHD.

•	Since the data we are dealing with is unbalanced, accuracy may not be the best evaluation metric to evaluate the mode 

•	Also, since we are dealing with data related to healthcare, False Negatives are of higher concern than False Positive

•	In other words, it doesn’t matter whether we raise a false alarm but the actual positive cases should not go undetected.

•	Considering these points, we decided to use Recall as the model evaluation metric.

•	It is critical that the model we develop has a high recall score. It is OK if the model incorrectly identifies a healthy patient as a high-risk patient because it will not result in death, but if a high-risk patient is incorrectly labeled as healthy, it may result in fatality.

•	The recall score of the KNN, Decision tree, and SVM are the highest among all the models we have used here and XG Boost has given us the lowest recall.

•	We were able to create a model with a recall of just 0.75 because of limitations in computational power availability. This indicates that out of 100 individuals with the illness, our model will be able to classify only 75 as high-risk patients, while the remaining 25 will be misclassified.

## Recommendations
- With more knowledge from an expert in the field of cardiovascular health, new variables could be developed to enhance the predictions further.
- Better models other than the ones used here could be used to improve predictions.
- This project has provided experience in an important field of healthcare and has clearly illustrated the application of machine learning in this field.

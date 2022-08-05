# Capstone_Project_ML_Classification_Cardiovascular_Risk_Prediction

Visiting hospitals for regular check-ups it is almost always seen that they encourage people to get special check-ups to identify if they are at risk of heart diseases. Heart diseases have unfortunately become very common. It may be due to various reasons such as lifestyle, work pressure, lack of exercise, etc. 

In this project, we will be working on predicting the 10-year risk of Coronary Heart Disease (CHD). We are given a set of variables that impact heart diseases. These variables are related to demographic, past, and current medical history.

The dataset is from an ongoing cardiovascular study on residents of the town of Framingham,
Massachusetts. The classification goal is to predict whether the patient has a 10-year risk of
future coronary heart disease (CHD). The dataset provides the patients’ information. 

It includes over 4,000 records and 15 attributes.
Variables.

Each attribute is a potential risk factor. There are both demographic, behavioral, and medical risk
factors.


This shows an overview of the Columns, non-null count and the data types of the dataset

Attributes:

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

# Stroke-Prediction-
Welcome to my analysis on Stroke Prediction! This project was completed as part of my coursework for the Math for Decision Analysis subject during my first semester. Here, I present various analyses and visualizations I conducted on Stroke Prediction data.

Introduction:
-> Research Question: What risk factors are most predictive of stroke occurrence?
Specifically, I want to analyze how demographics, medical history, and lifestyle behaviors influence stroke risk. Identifying key predictors could inform prevention efforts and screening to better manage high-risk groups.

This is an important issue as stroke is a leading cause of long-term disability and death globally [1]. Predictive analytics to estimate stroke risk could lead to earlier intervention, better outcomes for patients, and lower healthcare costs. Other related work has developed stroke prediction models using machine learning but with inconsistent variables and accuracy [2]. This analysis aims to clarify stroke predictors in the context of data from an American community health study. Others should care about these insights to better understand and reduce stroke burden.

Data
Source The data is originally from the CDC database hosted on Kaggle titled “Stroke Prediction Dataset” [3]. The data was collected from Kaggle at https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

Collection The dataset contains health information on 5110 patients from rural communities in Indiana, USA collected during multiple health campaigns within the state from Jan 2017-Oct 2019.

Units:
Each row in the dataset represents an individual or a patient, and the columns hold various attributes and measurements related to their health and lifestyle.

Variables :
The variables included cover demographics (gender, age, residence type), behaviors (smoking, BMI), medical history (hypertension, heart disease, glucose levels) and the target variable stroke (1 = patient had a stroke, 0 = no stroke).

Study type:
This was an observational study, collecting data from a community setting rather than an experimental trial.

Data Cleanup

1.Droped Column ID since its not useful

2.The “other” column of gender variable was considered as a outlier and hence removed.

3.Replaced the unknown in “smoking_status” variable with the most frequent category(never smoked)

4.BMI variable had a lot of missing values which were removed.

# Diabetes_Detection_Systems

## Problem statement
* Background:
Diabetes is a chronic medical condition characterized by elevated blood sugar levels due to either insufficient insulin production or the body's inability to use insulin effectively. Early detection and management of diabetes are crucial for preventing complications and improving the quality of life for individuals affected by the disease. Machine learning techniques have shown promise in identifying patterns and predicting diabetes risk based on various medical and lifestyle factors.

* Problem Description:
The aim of this project is to develop a machine learning model that accurately detects the presence of diabetes in individuals based on a set of input features. The model should be able to take into account relevant medical and demographic variables and provide a binary classification (diabetic or non-diabetic) for each individual.

## Dataset used 
The link of the dataset used can be found on [Kaggle Website](https://www.kaggle.com/datasets/mathchi/diabetes-data-set)

* About the dataset
* Context
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to predict based on diagnostic measurements whether a patient has diabetes.

* Content
Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

1. Pregnancies: Number of times pregnant
2. Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
3. BloodPressure: Diastolic blood pressure (mm Hg)
4. SkinThickness: Triceps skin fold thickness (mm)
5. Insulin: 2-Hour serum insulin (mu U/ml)
6. BMI: Body mass index (weight in kg/(height in m)^2)
7. DiabetesPedigreeFunction: Diabetes pedigree function
8. Age: Age (years)
9. Outcome: Class variable (0 or 1)


## Procedure Followed
* Importing the Dependencies for the functions going to used in the project.
* Data collection and Data preprocessing is done, using the value_counts() function find the number of different cases, groupby() the outcome and analyze the values.
* Since the data is having high variation, use Standard Scaler for standardization after dividing the values into two datasets x and y which are features and labels respectively.
* Split the x and y data into training values and testing values and then the data is fit into the Support Vector Machine Classifier Model.
* Accuracy is found and the Predictive model is built.

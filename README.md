Patient Classification Model: Inpatient vs. Outpatient
Project Overview
This project aims to build a machine learning model to classify patients as either inpatients or outpatients based on their medical and demographic data. The model utilizes a stacking classifier that combines multiple algorithms for improved prediction performance.

Dataset
The dataset used in this project contains the following features:

HAEMATOCRIT: A measure of the proportion of red blood cells in the blood.
HAEMOGLOBINS: A measure of the amount of hemoglobin in the blood.
ERYTHROCYTE: The count of red blood cells.
LEUCOCYTE: The count of white blood cells.
THROMBOCYTE: The count of platelets.
AGE: The age of the patient.
SEX: The gender of the patient (Male/Female).
The target variable is SOURCE, which indicates whether the patient is an inpatient or outpatient.

Model
The model used is a Stacking Classifier, which combines predictions from the following base models:

Decision Tree Classifier
Logistic Regression
Support Vector Classifier (SVC)
Random Forest Classifier
The final meta-model is a Logistic Regression, and the original features are passed through to the final estimator along with the base models' predictions.

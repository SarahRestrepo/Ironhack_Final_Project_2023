# Ironhack_Final_Project_2023
 
Objective:
	Analyze Stroke prediction data set and create a machine learning model to accurately predict if a person will have stroke based on risk factors.


Python

Cleaning the data

Checking for nulls – BMI had nulls. Used the mean to fill nulls.

Checking data types – Integers/Floats/Objects

Checking for duplicates – None identified

Drop columns – Id was dropped as they are not relevant to the model

Change column type to object type – Hypertension, Heart_disease, Stroke

Deleted row with 'Other' for gender

Used boxcox transformation to manage outliers

Used sns.barplot for further data visualization and discovery

Heatmap: age is correlated to stroke. Hypertension, Heart_disease and avg_glucose_level also have positive correlations to the target 

Dropped original 'bmi' and 'avg_glucose_level' and left the boxcar transformed data

Modeling data with scaled data and encoded data.

Used Logistic Regression, KNN = 5, KNN = 10, Random Forest, XGBoost

Random forest and XGBoost gave better accuracy and sensitivity scores.

	








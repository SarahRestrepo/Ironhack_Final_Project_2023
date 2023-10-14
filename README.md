# Ironhack_Final_Project_2023
 
Objective:
•	Analyze Stroke prediction data set and create a machine learning model to accurately predict if a person will have stroke based on risk factors.


Python
•	Cleaning the data
o	Checking for nulls – BMI had nulls. Used the mean to fill nulls.
o	Checking data types – Integers/Floats/Objects
o	Checking for duplicates – None identified
o	Drop columns – Id was dropped as they are not relevant to the model
o	Change column type to object type – Hypertension, Heart_diseas, Stroke
o	Deleted row with 'Other' for gender
o	Used boxcar transformation to manage outliers
o	Used sns.barplot for further data visualization and discovery
o	Heatmap: age is correlated to stroke. Hypertension, Heart_disease and avg_glucose_level also have positive correlations to the target 
o	Dropped original 'bmi' and 'avg_glucose_level' and left the boxcar transformed data
o	Modeling data with scaled data and encoded data.
	Used Logistic Regression, KNN = 5, KNN = 10, Random Forest, XGBoost
	Random forest and XGBoost gave better accuracy and sensitivity scores.

	








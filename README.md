# Advance-House-Price-Prediction
Advance House Price Prediction

Business Understanding:In this assignment, you are a Data Analyst working at a Real Estate Investment Trust. The Trust would like to start investing in Residential real estate. You are tasked with determining the market price of a house given a set of features. You will analyze and predict housing prices using attributes or features such as square footage, number of bedrooms, number of floors, and so on. 

Exploratory Data Analysis: Imported the data using Pandas library.Finding number of missing values for Categorical and Numerical variables using isnull() function. 
We have find the relationship between missing values and Sales Price using barplot visualization.Have analysed continous variables using histogram.Found Outliers using Box Plot for continous feature.

Feature Engineering: Handling missing values for both categorical and numerical features. Replacing missing values for numerical values with their median values because it has outliers which we have observed during Exploratory Data Analysis. Created new labels missing for Categorical variables where data is missing.Since the numerical variables are skewed we will perform log normal distribution. We have removed categorical variables that are present less than 1% of the observations. Scaled the data from 0 to 1 using MinMaxScaler


Feature Selection: Imported Lasso and SelectFromModel module from Scikit Learn Library to select important features from 83 available features.



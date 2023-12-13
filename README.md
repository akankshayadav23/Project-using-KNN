# Advanced Project 5&6
# Project-5
# iPhone purchase prediction model

# Overview of Model
### Objective:
Develop a predictive model using the K-Nearest Neighbors (KNN) algorithm to determine whether a customer will purchase an iPhone from a store. The prediction is based on three key features: Gender, Age, and Salary. This model aims to assist stores in understanding customer behavior and optimizing marketing strategies.

# Dataset
Columns:
Gender
,Age
,Salary
,Purchase iPhone

# Model Used
### K-Nearest Neighbors (KNN)

# Methodology
### 1. Requirements:
Python

pandas

seaborn

scikit-learn

matplotlib
### 2. Exploratory Data Analysis (EDA):

Explored the dataset's structure, summary statistics, and correlation.

Visualized relationships between selected numeric variables using pairplots.

Gained insights into potential predictors affecting the outcome.

### 3. Data Exploration:

Explored the dataset to understand the distribution of features.
Checked for any patterns or trends in iPhone purchases.
### 4. Feature Selection:

Selected key features: Gender, Age, and Salary as predictors.
Defined 'Purchase iPhone' as the target variable.
### 5. Model Selection:

Chose K-Nearest Neighbors (KNN) as the predictive model.
Configured the model to find the nearest neighbors based on feature similarity.
### 6. Model Training:

Split the dataset into training and testing sets.
Trained the KNN model on the training data.

### 7. Model Evaluation:

Evaluated the model's performance using metrics such as accuracy, precision, and recall.
Assessed the ability of the model to correctly predict iPhone purchases.

# Project-6 
# House Price Prediction in Bangalore 
# Model used:
### K-Nearest Neighbors (KNN)

# Objective

 Implement a predictive model using the K-Nearest Neighbors (KNN) algorithm to estimate the price of houses in Bangalore. The prediction is based on several features including the number of bathrooms, balconies, total square footage, price per square foot, and different locations. This model aims to assist potential homebuyers, sellers, or real estate agents in estimating house prices based on key attributes.

# Dataset:
Name : Bangalore House price 
Columns :Bathrooms
,Balcony
,Total sqft
,Price per sqft
,Different locations
,Price (Target Variable)

# Methodology 

### 1. Requirements 

Pandas
Seaborn
Matplotlib
Scikit-learn

### 2. Data Exploration:

Explored the dataset to understand the distribution of features.
Analyzed correlations and relationships between variables.
### 3. Feature Selection:

Selected key features: Bathrooms, Balcony, Total sqft, Price per sqft, Different locations.
Defined 'Price' as the target variable.

### 4. Model Selection:

Utilized K-Nearest Neighbors (KNN) for the regression task.
Configured the model to find nearby houses based on feature similarity.

### 5. Model Training:

Split the dataset into training and testing sets.
Trained the KNN regression model on the training data.

### 6. Model Evaluation:

Evaluated the model's performance using regression metrics such as Mean Absolute Error (MAE) or Root Mean Squared Error (RMSE) and accuracy score 
Assessed the ability of the model to accurately predict house prices.

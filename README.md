# King-County-House-Sales
# 1. Introduction
## Business Understanding
When done strategically, remodeling improves your home’s value and marketability. You might notice that a home that is similar to your home in age, size and layout has been appraised at a much higher value than your home. The most likely reason is that the home has been upgraded. Homes that have been upgraded with modern features or layouts attract more homebuyers and higher offers.

Updating or improving aging systems can increase energy efficiency and resale value. Because the physical characteristics of your home depreciate in value, a newer home will have a higher value than an older home. Home appraisers rate your home’s condition based on the amount and degree of repairs required. A well-maintained older home with a sound foundation and structure and functional systems will also have a higher value.

Buyers in particular should take note of your home’s age based on the quality and design of materials and fixtures. When you maintain your home from a structural and aesthetic standpoint, you improve your property value.
## Problem Statement
The business problem is to provide advice to homeowners about how home renovations might increase the estimated value of their homes using multiple linear regression to predict the estimated value of homes in King County.
## Main Objective
The main objective of this project is to develop a multiple linear regession model that predicts the estimated value of homes in King County. 
## Defining the metrics for success
The project would be considered a success if the predictive model achieves an R-Squared value of at least 80% and the Mean Absolute Percentage Error (MAPE) of the model is less than or equal to 10%.

## Experimental Design
1. Data Collection. Here we will describe how the King County Sales dataset was obtained and any data preprocessing steps that were performed such as handling missing values, data cleaning and feature selection.
2. Exploratory Data Analysis. Here we will summarize the initial exploration and visualization of the dataset to see the distribution of variables, identify any outliers and understand the relationships between features and the target variable.
3. Feature Engineering. Here we will perform encoding on categorical variables.
4. Model Building. Here we will outline the process of building the multiple linear regression model by selecting the relevant features, splitting the data into training and testing sets, fitting the model to the training data, and evaluating the model's performance using appropriate validation techniques.
5. Model Evaluation. Here we will check the coefficients of the models.
6. Conclusion. Here we will summarize the findings from the analysis.
7. Reccomendation. Here we will give recommendations for the homeowner based on the model results.

## Data Understanding
The data that was  used in this project was collected from the King County House Sales dataset. The description of the column names can be found in column_names.md.
# Conclusions
- The baseline model has a Root Mean Squared Error of 1.39e-9 and explains 100% of the variance.
- The feature selection model has a Root Mean Squared Error of 1.38e-9 and explains 100% of the variance.
- The Linear regression model has a Root Mean Squared Error of 243998.85 and explains 55% of the variance.
- The Polynomial regression model has a Root Mean Squared Error of 1.38e-9 and explains 60% of the variance.
- The feature selection model has the best balance of coefficients.
# Reccomendations
- The model we should use the feature selection model as it has the lowest Root Mean Squared Error which indicates a better model performance.
- It would also be recommended that we use the feature selection model since it explain 100% of the variance showing thatthe whole proportion of the variance is accounted for by the model.
- There is a linear relationship between the price and square foot of living for homeowners who want to develop pricier units for commercial purposes.

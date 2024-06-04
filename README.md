# BoomBikes Bike sharing MLR Assignment
> This assignment is about building a multiple linear regression model for the prediction of demand for a business which is in the business of offerring shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project is about building a multiple linear regression model for the prediction of demand for a business which is in the business of offerring shared bikes.
- Business Objective 1 - Which variables are significant in predicting the demand for shared bikes.
- Business Objective 2 - How well those variables describe the bike demands
- Objective 1 - To model the demand for shared bikes with the available independent variables.
- Objective 2 - The model should help to understand how exactly the demands vary with different features.
- Objective 3 - The model may help management to understand the demand dynamics of a new market.
- Present a set of Insights and Recommendations based on 'Consumer attributes' and 'Loan attributes' to the Company, so that 
- A dataset is provided which contains bike sharing data of 2 years, 2018 and 2019

## Approach
1. Data Understanding and Cleaning
    1. Check missing or null values and remove/impute, if any
    2. Remove the columns which may not conribute in further analysis
    3. Data preparation: converting column to categorical variable
    4. Univariate analysis
    5. Handling outliers
    6. EDA
    7. Correlation analysis
2. Linear Regression Data preparation
    1. Create dummy variable
    2. Split the data into train and test dataset
    3. Feature Scaling/Normalization
    4. Mark target column and feature columns
3. Creating Regression Model - Iterative model process
4. Model Evaluation:
    1. Residual analysis
    2. Dependency among Error terms
    3. Homoscedasticity of error terms
5. Making Predictions Using the Final Model
6. Model evaluation
7. R-squared score on the test set


## Conclusions
After couple of iterations a suitable model has been devised which fits the requirements.

## Technologies Used
- Python - version 3.11.7
- pandas - version 2.1.4
- numpy  - version 1.26.4
- seaborn - version 0.12.2
- matplotlib.pyplot - version 3.8.0
- plotly.express - version 5.9.0
- sklearn version - 1.2.2
- statsmodels version - 0.14.0

## Other tools Used
- Python v3.11.7
- Anaconda package
- Jupyter notebook
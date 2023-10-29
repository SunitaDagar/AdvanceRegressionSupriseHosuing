# AdvanceRegressionSupriseHousing
Advance Regression Surprise Housing

Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Business Goal
This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

Solution Approach
Data Understanding & Analysis & Preparation- Treating Missing value and outlier
Data Transformation and Preprocessing
Test Train Split and Scaling
Model Prediction and Evaluation ( MLR ,Ridge and Lasso Regression )
Conclusions and Results

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- Determine the optimal value of lambda for ridge and lasso regression.
- This model will then be used by the management to understand how exactly the prices vary with the variables
- They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
- The model will be a good way for the management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Out of 40 features in the final model, top 10 features in order of descending importance are 1stFlrSF, OverallQual, 2ndFlrSF, OverallCond, LotArea,BsmtFinSF1, GarageArea, BsmtQual, Neighborhood_Somerst, SaleType_New
- Lasso Regression is chosen as final model for having slightly better R-square value on test data.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.8
- Panda - version 2.0.3
- Matplotlib - version 3.4
- Seaborn - version 3.0
- sklearn - version 3.0
- statsmodels - version 3.0
- IDE - Jupyter Notebook - version 6.5.2


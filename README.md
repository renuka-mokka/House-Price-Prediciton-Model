# House Price Prediction using Advanced Regression concepts
> Goal is to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not. Need to understand the important predictors of house price and how well those factors drive the price of house property.

 
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information

Background:
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

Busines Goal:
- You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
  
Dataset:
- Housing data set is given as sample to work on building the model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
#### Ridge and Lasso gives similar results but Lasso giving slightly better test results, so we can choose lasso if we want to avoild multi collinearity.
#### If we want a model without loosing features, then we can choose Ridge regression.

- Below are top 10 features which are driving the house prices in positive manner according to ridge regression :

#### 1. GrLivArea      - Above grade (ground) living area square feet
#### 2. 1stFlrSF         - First Floor square feet
#### 3. BsmtFinSF1   - Type 1 finished square feet
#### 4. OverallQual    - Rates the overall material and finish of the house
#### 5. TotalBsmtSF  -  Total square feet of basement area
#### 6.TotRmsAbvGrd  - Total rooms above grade (does not include bathrooms)
#### 7. 2ndFlrSF     - Second floor square feet
#### 8.OverallCond   - Rates the overall condition of the house
#### 9.LotArea    -  Lot size in square feet
#### 10. MasVnrArea    - Masonry veneer area in square feet


- The optimal value of lambda for Ridge regression – 4
- The optimal value of lambda for Lasso Regression – 100
- The results are very much improved in Ridge and Lasso compared to Linear Regression.
#### Ridge and Lasso results are very similar results  in this model, I would prefer to choose Lasso regression as we are getting better test results, also we can avoid highly correlated features.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Tools -Jupyter notebook
- Language - Python
- Concepts - Linear regression, Ridge regression, Lasso regression


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@renuka-mokka] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

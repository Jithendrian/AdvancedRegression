# Advanced Regression Assignment 
> An Advanced Linear Regression Assignment with using Ridge and Lasso.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Miscellaneous](#miscellaneous)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.*

#### Business Goal:

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

### Ridge
#### Top indicators with optimal alpha
- GrLivArea
- Neighborhood_Crawfor
- OverallQual
- Exterior1st_BrkFace
- Functional_Typ
- Condition1_Norm
- SaleCondition_Alloca
- SaleCondition_Normal
- OverallCond
- TotalBsmtSF <br/>

#### Metrics with optimal alpha: 
- Optimum alpha value 20
- R-Squared (Train) 0.93
- R-Squared (Test) 0.93

### Lasso
#### Top indicators with optimal alpha
- GrLivArea
- Neighborhood_Crawfor
- Exterior1st_BrkFace
- OverallQual
- Functional_Typ
- Condition1_Norm
- TotalBsmtSF
- OverallCond
- Neighborhood_Somerst
- Neighborhood_NridgHt <br/>

#### Metrics with optimal alpha: 
- Optimum alpha value 0.001
- R-Squared (Train) 0.92
- R-Squared (Test) 0.93

## Technologies Used

- matplotlib 3.7.2
- sklearn 1.3.0
- pandas 2.1.0
- numpy 1.25.2
- seaborn 0.12.2
- statsmodels 0.14.0
- python 3.10+

## Acknowledgements
- Thanks to upgrad/ IIITB and also to the instructors for providing this assignment. Good learning experience

## Contact
- Created by [@jithendrian] (https://github.com/Jithendrian/AdvancedRegression) 

- jithendrian@gmail.com 
- Assignment
    - Main folder : https://github.com/Jithendrian/AdvancedRegression
    - Python/ ipynb : https://github.com/Jithendrian/AdvancedRegression/blob/main/AdvancedRegression.ipynb

    - Subjective questions : https://github.com/Jithendrian/AdvancedRegression/blob/main/Assignment_Part2.pdf
    


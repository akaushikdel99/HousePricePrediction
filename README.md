# House Price Prediction Assignment
> Surprise Housing, a US-based company, is planning to enter the Australian market by leveraging data analytics to buy undervalued houses and sell them at a profit. The company has gathered a dataset of house sales in Australia and aims to build a regression model with regularization to predict the actual value of prospective properties. The goal is to identify the variables that significantly predict house prices and understand their impact. The model will also help determine the optimal value of lambda for ridge and lasso regression. This model will guide the company's investment decisions and help the management understand the price variations with different variables, enabling them to strategize for high returns and gain insights into the new market's pricing dynamics.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#Contact)

## General Information
Surprise Housing, a US-based company, is planning to penetrate the Australian market. They use data analytics to buy houses below their actual value and sell them at a higher price. To facilitate this, they have gathered a dataset from house sales in Australia.

The objectives of this assignment are:

1. **Model Development**: Build a regression model with regularization to predict the actual value of prospective properties.
2. **Variable Identification**: Determine which variables significantly predict house prices and how well they describe the price.
3. **Optimization**: Find the optimal value of lambda for ridge and lasso regression.
4. **Business Strategy**: Use the model to guide investment decisions, manipulate the firm’s strategy for high returns, and understand the pricing dynamics of the new market.

## Conclusions
Based on 3 models that we have prediced Lasso seems to provide better accuracy. Below are few conclusions of model

- lasso works best with alpha of 0.0001
- ridge works best with alpha of 3.3
- lasso got higest r2 of 93 followed by ridge then vanilla linear with RFE

Based on Lasso following are the 10 key columns that influence the price of property
   - GrLivArea
   - OverallQual
   - BsmtFinSF1
   - OverallCond
   - GarageArea
   - YearBuilt
   - BsmtUnfSF
   - LotArea
   - Neighborhood_StoneBr
   - Neighborhood_NoRidge


## Technologies Used
- pandas
- matplotlib
- seaborn
- sklearn
- statsmodel


## Contact
Created by [@akaushikdel99] - feel free to contact me!

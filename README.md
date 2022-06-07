# House_Price_Prediction_Assignment
This assignment is based on Advance Regression with Ridge &amp; Lasso implementation to predict the house price based on certain variables

# Project Name
> Advance_Regression_Assignment_House_Price_Prediction



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
-A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.

Assignment Part-II

Question 1
What is the optimal value of alpha for ridge and lasso regression? What will be the changes in the model if you choose double the value of alpha for both ridge and lasso? What will be the most important predictor variables after the change is implemented?

Question 2
You have determined the optimal value of lambda for ridge and lasso regression during the assignment. Now, which one will you choose to apply and why?

Question 3
After building the model, you realised that the five most important predictor variables in the lasso model are not available in the incoming data. You will now have to create another model excluding the five most important predictor variables. Which are the five most important predictor variables now?

Question 4
How can you make sure that a model is robust and generalisable? What are the implications of the same for the accuracy of the model and why?


## Conclusions
Even though the r2_score of Ridge is slightly higher for the test dataset,its better to use Lasso as it assigns a zero value to insignificant features,thus helping us to choose the correct variables.Also its preferred to use simple yet robust model always.

## Technologies Used
pandas , numpy , matplotlib.pyplot , seaborn , train_test_split , MinMaxScaler , RFE , LinearRegression , statsmodels.api , mean_squared_error , r2_score ,sklearn , Ridge , Lasso , GridSearchCV  


## Contact
Created by [@swetasarkar9211] - feel free to contact me!

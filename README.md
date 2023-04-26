# Advanced Regression Assignment
> Purpose of this assignment is to make the suitable model to make the correct prediction for the house price with given significant variables and used a supervised learning technique.

![image](https://user-images.githubusercontent.com/72481400/233831432-52458dfb-3ac3-43c2-9866-1c4e73df40e6.png)
                                                        



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
This assignment contains two parts. Part-I is a programming assignment, and Part-II includes subjective questions. 

### Assignment Part-I
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

### Business Goal 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

### Assignment Part-II 
Submit Below question answer-

Question 1
What is the optimal value of alpha for ridge and lasso regression? What will be the changes in the model if you choose double the value of alpha for both ridge and lasso? What will be the most important predictor variables after the change is implemented?

Question 2
You have determined the optimal value of lambda for ridge and lasso regression during the assignment. Now, which one will you choose to apply and why? 

Question 3
After building the model, you realised that the five most important predictor variables in the lasso model are not available in the incoming data. You will now have to create another model excluding the five most important predictor variables. Which are the five most important predictor variables now?

Question 4
How can you make sure that a model is robust and generalisable? What are the implications of the same for the accuracy of the model and why?



## Conclusions

We getting below mentioned optimal value for lambda -

Ridge - 3.0

Lasso - 0.0001

r2 value we got is:


Ridge - Train = 0.924302 , Test = 0.896

Lasso - Train = 0.90598, Test =0.906866


The Mean Squared error value we got is:

Ridge test - 0.046756

Lasso test - 0.046535


We can clearly observe that the Mean Squared Error of Lasso is slightly lower than that of Ridge.

## Technologies Used
- numpy - Version: 1.21.5
- pandas - Version: 1.4.4
- matplotlib - Version: 3.5.2
- seaborn - Version: 0.11.2
- sklearn - version 0.24.2
- statsmodels - Version: 0.13.2



## Contact
Created by [@teekamkhandelwal] - feel free to contact me!


**Note:-**
* **Data used for this project persent in data folder.**
* **Advanced Regression Subjective Questions (Assignment Part-2) answer file  as a pdf is also persent in Data folder.**
* **python programming file is persent in Python folder** 



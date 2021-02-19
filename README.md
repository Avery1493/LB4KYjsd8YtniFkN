# Happy Customers  
Task: Predict if a customer will be happy or unhappy based on survey results.  
Data Description:  
Y = target attribute (Y) with values indicating 0 (unhappy) and 1 (happy) customers  
X1 = my order was delivered on time  
X2 = contents of my order was as I expected  
X3 = I ordered everything I wanted to order  
X4 = I paid a good price for my order  
X5 = I am satisfied with my courier  
X6 = the app makes ordering easy for me  
Attributes X1 to X6 indicate the responses for each question and have values from 1 to 5 where the smaller number indicates less and the higher number indicates more towards the answer.  

# Model  
Random Forrest Model  
First random forrest model produced a testing accuracy of .6792. From looking at the feature importances, I concluded that attribute X4 and X6 were least importing in contributing to the accuracy score.  
The second model was used to determine how the accuracy would be affected if those two attribute were excluded from the predictive model. 

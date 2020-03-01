# Credit Score using Machine Learning
Using machine learning to create a credit score to customers

## Multiple Linear Regression in Python with Scikit-Learn

We just performed linear regression in the above section involving two variables. Almost all the real-world problems that you are going to encounter will have more than two variables.

Linear regression involving multiple variables is called “multiple linear regression” or multivariate linear regression. The steps to perform multiple linear regression are almost similar to that of simple linear regression.

We will use customer information to generate a 'trust' score on the customer. The score formula can be adapted for each company according to its credit context. In this example we are going to use the average number of days the customer is late, and the average billing amount for the past 2 years to calculate a score that combines the 2 information.

After calculating the score, we submit the information to a machine learning with Scikit-Learn, so that the system can predict new scores based on the learning information.


Our formula for Score calculation described on: Score calculation.xlsx

Our customer information: Customers_CODE.XLSX

### Customer company information
 > Customer from date
 
 > State, Region, Postcode, Salesman, Main CNAE (type of company classification in Brazil)
 
 > Highest Billing Date
  
 > Maximum billing amount
  
 > Last Date invoice issued
 
 > Largest credit exposure date
 
 > Highest credit exposure
 
 > Average historical delay
 
 > Average revenue last 48 months  
 
 > Amount payable Overdue
 
 > Amount payable due
 
 > Customer Last Order Date
 
 > Date of this information
 
### SERASA Information ( Serasa it's a company that sell's information about other companies)
 
 > Serasa Score 
 
 > Probability of not paying
  
 > Last date non payment

 > Amount of unpaid documents

 > Value of unpaid documents
  
 > Last date bad checks
 
 > Amount of bad checks
  
 > Last date protests

 > Value protests
  
 > Last date judicial actions

 > Value judicial actions
  
 > Last date overdue debts

 > Value overdue debts

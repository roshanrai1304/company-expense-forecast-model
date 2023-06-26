# company-expense-prediction-model
The goal of the project is to build a model which could predict the future expenses of the company by training the model on previous year data.

## Dataset
This is a dummy dataset created by me and it contains the expense of different department's of the company each month. 
Columns of Dataset
year: Specifies the year of the expense made
month: Specifies the month of the expense made
debt: debt represents the amount of money that the company spent in that month for paying their debt.
rent: rent represents the amount of money that the company spent in that month paying their rent.
employee_salary: The amount of money that the company spent on employees in that month.
marketing: marketing represents the amount of money that the company spent on marketing its product.

## Model Building
This is the problem of type multiple input and multiple output time series problem in which we will be taking data from previous 6 months and trying to predict the expense in the future. As this is a time series problem we will be using LSTM in the network.


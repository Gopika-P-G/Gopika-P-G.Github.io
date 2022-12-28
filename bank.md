# Customer Segmentation using K-mean method

In this project, Im going to pretent as a data scientist at a bank.
I'm presented with data on the bank customer for past  6month.
Data includes Tenure, Transaction frequency, Credit limit etc.
Bank wants to divide its cutomer in to atleast 3 distinct group.
Here I'm using K-mean clusturing to divide the customer in to distinct group.

Data source:Kaggle

Tools: Jupyter Notbook, Numpy, Pandas, Matplotlib, Seaborn, Scikit-Learn.

Report:

Insights gained from Data exploration and Visulization
1.Average balance of the customers are  15000
2.Most of the customer update their balance frequently
3.Very small amount of customer pay their amout in full payment
4.For tenure lot of the customer are around 11 year
5.Purchases has high correlation with one off purchases, Installment purchases and purchase transaction


Algorithm:
K-mean is an unsupervised learning algorithm.
It works by grouping similar kind of data together by measuring Euclidian distance between points

Using K-mean grouped the customer in to 4 category:
Transactor: Customer who pay least amount of interest
Revolvers: Customer who use their credit card as a loan
New Customers: New Customer with low tenure
VIP/Prime: Customer with high Credit limit


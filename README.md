# Regression_Classification
This is a simple classification problem, where we are given dataset for a Portuguese bank's marketing campaign to get customers to subscribe to a term deposit. The aim is to predict if a customer will subscribe to the deposit, given certain pieces of information about the customer.

You can find the exact case description and the data dictionary here: https://archive.ics.uci.edu/ml/datasets/bank+marketing

All the operations and the reasoning is provided in the code comments!

The file: term_deposit.ipynb contains:
a- Exploratory Data Analysis of the given data
b- Cleaning the data and handling outliers and multicollinearity
c- Balancing the data
d- Building a regression model for prediction, and finding the odds of each variable
e- Generating a pre-pruned decision tree to achieve better accuracy

The file: Loan Predictors.ipynb is an attempt to check if the demographic features provided in the file can act as predictors for the likelihood of loan application for a customer
a- Created a regression model, but could achieve only 58% accuracy
b- Created a decision tree, which was slightly more accurate but not up to the mark
c- Conclusion: The given demographic features are not good predictors of loan applications.

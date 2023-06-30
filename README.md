# MachineLearning-DefaultCreditCards

## Project Description 

The objective of this project is to develop a predictive model that can accurately forecast instances of customer default payments in Taiwan. By focusing on risk management, we aim to go beyond a simple binary classification of clients as credible or not credible. Instead, our emphasis is on estimating the probability of default for each customer. This approach provides a more valuable and nuanced understanding of the risk involved.

To assess the effectiveness of our predictive model, we will utilize a K-S chart. This chart allows us to evaluate and compare the performance of our model in identifying customers who are likely to default on their credit card payments. By analyzing the K-S chart, we can make informed decisions and take appropriate actions to mitigate potential default risks.

## Data Description

In this research, we examined the relationship between credit card default and various factors. The response variable, default payment, was represented by a binary variable where "Yes" indicated default (1) and "No" indicated no default (0). To analyze this, we considered a comprehensive set of 23 explanatory variables based on existing literature. 

Here is a detailed description of these variables:

1. X1: Amount of credit given in New Taiwan (NT) dollars, which includes both individual consumer credit and supplementary credit for the consumer's family.

2. X2: Gender, where 1 represents male and 2 represents female.

3. X3: Education level, categorized as follows: 1 = graduate school, 2 = university, 3 = high school, 4 = others.

4. X4: Marital status, classified as follows: 1 = married, 2 = single, 3 = others.

5. X5: Age of the individual in years.

6. X6 - X11: History of past payment. We examined the payment records from April to September 2005, where X6 represents the repayment status in September 2005, X7 represents the repayment status in August 2005, and so on. The scale used for measuring the repayment status is as follows: -1 = payment made duly, 1 = payment delayed by one month, 2 = payment delayed by two months, and so on, up to 9 = payment delayed by nine months or more. (# of months the amount has been due)

7. X12-X17: Amount of the bill statement in New Taiwan (NT) dollars. X12 represents the bill statement amount in September 2005, X13 represents the bill statement amount in August 2005, and so forth, up to X17 representing the bill statement amount in April 2005. (Amount Owed previously)

8. X18-X23: Amount of previous payment in New Taiwan (NT) dollars. X18 represents the amount paid in September 2005, X19 represents the amount paid in August 2005, and so on, up to X23 representing the amount paid in April 2005. (Amount Paid previously)

By analyzing these variables, we aim to gain insights into the factors that contribute to credit card default and develop a predictive model for identifying customers at risk of defaulting in the future.

## Project Objective

The objective of our project is to predict potential customers who are likely to default on their credit card payments in the upcoming months. Before delving into the details, let's first understand the definition of credit card default.

1. Understanding Credit Cards
- A credit card is a payment card that allows users to make purchases by utilizing a line of credit instead of using their own cash deposits. When a person uses a credit card for a transaction, they accumulate a balance that needs to be paid off on a monthly basis.

2. Defining Credit Card Default
- Credit card default occurs when an individual becomes significantly delinquent in making their credit card payments. It should be noted that missing a payment or two does not automatically result in default. Defaulting on a credit card payment happens when the Minimum Amount Due is not paid consecutively for several months.

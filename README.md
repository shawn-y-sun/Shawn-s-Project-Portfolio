# Project Portfolio
_Shawn Sun_


## [Project 1: Customer Analytics for Retail Company](https://github.com/shawn-y-sun/Customer_Analytics_Retail)

#### Overview
This project aims to support a retail or FMCG (fast-moving consumer goods) company to formulate marketing and pricing strategies that could maximize revenues on each brand of candy bars. To reach the fullest potential of bringing up revenues, a company should find the 'sweet spot' for price to maximize three customer behaviours: purchase probability, brand choice probability, and purchase quantity. 

Data from customer purchase history were used for training the regression models to predict those three customer behaviours in a preconceived price range. The results were then converted into price elasticities so that we can examine the effects of changing price on each of the behaviours. Hence, we will be able to find the suitable marketing and pricing strategies.

To better position our products, we will firstly perform segmentation on our customers to support our analysis on customer behaviours, allowing us to customize marketing strategies for customers with different backgrounds.

#### Code and Resources Used
* __Python Version__: 3.8.5
* __Packages__: pandas, numpy, sklearn, scipy, matplotlib, seaborn, pickle
* __Algorithms__: clustering(K-means, PCA), regression(logistic, linear)

## [Project 2: Credit Risk Modeling for Loan Defaults](https://github.com/shawn-y-sun/Credit_Risk_Model_LoanDefaults)

#### Overview
This project aims to measure the credit risk of a lending institution (i.e. a commercial bank) by calculating the expected loss of the outstanding loans. Credit risk is the likelihood that a borrower would not repay their loan to the lender. By measuring the risk effectively, a lender could minimize its credit losses while it reaches the fullest potential to maximize revenues on loan borrowing. It is also crucial for banks to abide by regulations that require them to conduct their business with sufficient capital adequacy, which, if in low, will risk the stability of the economic system.

The key metric of credit risk is Expected Loss (EL), calculated by multiplying the results across three models: PD (Probability of Default), LGD (Loss Given Default), and EAD (Exposure at Default). The project includes all three models to help reach the final goal of credit risk measurement.

#### Code and Resources Used
* __Python Version__: 3.8.5
* __Packages__: pandas, numpy, sklearn, scipy, matplotlib, seaborn, pickle
* __Algorithms__: regression (logistic, multiple linear)


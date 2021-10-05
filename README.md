# SupervisedLearning_BankLoan
This case is about a bank (Thera Bank) whose management wants to explore ways of converting its liability customers to personal loan customers while retaining them as depositors.
## Goal
To predict the likelihood of a liability customer buying personal loans.
## Data attributes
* Customer ID: It is the just a identification of the customer of the bank. This attribute wont help us in predicting the future potential loan customers. We can neglect this feature for our model prediction.
* categorical variables:
- Family : family size of the customer; has the values 1,2,3,4
- Education : Education Level. 1: Undergrad; 2: Graduate; 3: Advanced/Professional
- Securities Account : Does the customer have a securities account with the bank? ; column has value 0 or 1
- CD Account : Does the customer have a certificate of deposit(CD)account with the bank? ; column has value 0 or 1
- Online : Does the customer use internet banking facilities? column has values 0 (No) or 1(Yes)
- Credit card : Does the customer use a credit card issued by UniversalBank? ; column has values 0 (No) or 1(Yes)
* Interval varaibles:
- Age - Age of the customer ; has the range between 23 to 67
- Experience - Years of professional experience of the customer; ranges from 0 to 43, and there are few negative experiences
- Income - Annual income of the customers in dollars ; from  8000𝑡𝑜  224000
- CCAvg - Average credit card spending of the customer per month; data ranges from  000𝑡𝑜 10000
- Mortage - Value of House Mortgage if any; for the customer who doesnt have any mortage have got the value as 0 for this column
-Zip code - zip code of the home address of the customer

* Target Variable 
 - Personal Loan :Did this customer accept the personal loan offered in the last campaign?
## Machinelearning Alogorithms Explored
* Logistic Regression
* KNN
* GaussianNB
## Performance of the models
* LR: mean-accuracy= 0.908800 (stddev-accuracy= 0.007756)
* KNN: mean-accuracy= 0.898600 (stddev-accuracy= 0.008902)
* NB: mean-accuracy= 0.885600 (stddev-accuracy= 0.010385)

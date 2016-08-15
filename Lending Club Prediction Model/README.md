
Predicting Good Loans From Lending Club Loan Data

In this project, I am going to build a model to predict whether approve or reject new loan applications based on the historical datasets. I will be using the publicly available dataset of Lending Club issued loan data from 2007 to 2016 Q1.

I will approach this as a categorial problem by classifying the 'grade' variable into Good and Bad to indicate applicants' risk and treat the binary variable as my response variable. My model should return Good or Bad when evaluating new applicants.

I'm planning to first clean my data, then implement either PCA or LDA to reduce the 110 dimensions to 10 in order to find interesting variables. After that, I'm going to investigate what variables have significant influences between good applicants and bad applicants. Then I will apply models like random forest to train my data, with cross validation to test.

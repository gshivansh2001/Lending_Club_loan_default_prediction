## predicting Loan-Defaults on Lending-Club Dataset
LendingClub is a US peer-to-peer lending company and the world's largest peer-to-peer lending platform. It is the first peer-to-peer lender to register its offerings as securities with the Securities and Exchange Commission, and to offer loan trading on a secondary market.

In this project we will predict bad loans from Lending Club data to determine what constitutes a risky lending. Each line item in the data corresponded to a loan, and had various features relating to loan amount, employment information of the borrower, payments made, and the classification of the loan as charged off or active with any delays in payments noted.

An exploratory data analysis was performed on the data using NumPy, Seaborn, Matplotlib and Pandas,  to look for outliers and individual distributions of the variables. Following which, the interactions between these variables were studied to weed out highly correlated variables. Then using a Deep Neural Network we bulit the model to predict the defaulting loans.

# CreditCardFraudData
A free Kaggle dataset tracking two days' worth of European credit card transactions, some labeled fraudulant

The first 28 columns are the results of PCA on the data. The "Time" column tracks the time elapsed since the first transaction recorded. "Amount" is the actual euro(?) value of the transaction, and "Class" describes whether the transaction was labeled as fraudulent, (1 is fraudulant, 0 is not)

Initially, I want to try cluster analysis and see if the 'fraud' and 'non-fraud' classes might be separable by a SVM.

# Readme-styling


I have used KNN and VotingClassifier to classify the stocks into three categories

1. Buy labelled 1
2. Sell labelled -1
3. Hold labelled 0

The features are the percentage changes over a period of 7 days. I have made decisions based on (+/-) 2% change and assigned labels for the Stocks.

(Note - I have mentioned all the Stocks by their ticker values as per Nifty.)

Then The pct_change is used to make the feature set and this is fed into KNN and Voting Classifier that includes KNN, RandomForest and SVM combined. 
Accuracies of the Classifiers are compared.

Sidenotes:
- I have gathered the company list from [Wiki for Nifty](https://en.wikipedia.org/wiki/NIFTY_50) 
- The yahoo finance website is used to get the dataset using Pandas_datareader

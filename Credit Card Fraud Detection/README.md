# Credit Card Fraud Detection

Fraud is a problem for any bank. Fraud can take many forms, whether it is someone stealing a single credit card, to large batches of stolen credit card numbers being used on the web, or even a mass compromise of credit card numbers stolen from a merchant via tools like credit card skimming devices.

## Overall Task:

Build a predictive model to determine whether a given transaction will be fraudulent or not.

## Datasets: 
I used the credit card transactions dataset for this project. This data, which is in line-delimited JSON format, can be found [here](https://github.com/CapitalOneRecruiting/DS). Note that this dataset loosely resembles real transactional data from Capital One credit card customers, but the entities and relations within are purely fictional. No persons, places, or things lost their identity in the making of this dataset.

## Summary:
Created classification models such as Logistic Regression, Random Forests, Ada Boost, Catboost, and XGB to detect fraudulent behavior based on imbalanced fraudulent credit card transaction datasets (AUC=0.73 on Test).

## Important Features:
According to the Random Forest ML model, the top 10 features that can identify fraud transactions are:

- Transaction Amount
- POS Entry Mode = 05 or 09
- Card Present
- Credit Limit
- Merchant Category Code = 'Fuel' or 'Online Retail' or 'Fast food'
- Month of transaction


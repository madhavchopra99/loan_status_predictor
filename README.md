## Problem Statement

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. Here they have provided a partial data set.

For more info check [kaggle](https://www.kaggle.com/datasets/ninzaami/loan-predication)

## Solution

Our solution using Support Vector Machine as machine learning core boasts 77% of accuracy.

The model is saved as pickle file at path /model/model.pkl.

## Dependencies

* Numpy
* Pandas
* Scikit-learn
* Seaborn

## Screenshots

![Dependency on Education](https://raw.githubusercontent.com/madhavchopra99/loan_status_predictor/main/screenshot/education.png)
![Dependency on Marital Status](https://raw.githubusercontent.com/madhavchopra99/loan_status_predictor/main/screenshot/marital_status.png)

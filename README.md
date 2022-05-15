# Introduction

In this project, you need to identify fraudulent transactions from credit card data (1 for fraud and 0 for normal). The dataset is highly imbalanced, meaning the positive class (fraudulent transactions) only accounts for about 0.2% of the training data. You need to develop strategies for dealing with imbalanced datasets.

For this project, there are no constraints to the machine learning model. You should try to apply the models we have learned from this course so far.

You will be evaluated over the AUC score on the private leaderboard. Note that you will not see your private leaderboard score before the submission deadline. This competition will close on November 18th.

# Data Description

The dataset contains credit card transactions from September 2013 by European cardholders. Due to privacy concerns, the actual features have been transformed using Principal Components Analysis (PCA), which has no intrinsic meaning. The only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction. The feature 'Class' is the target variable. “Class” takes a value of 1 in case of fraud and 0 otherwise.

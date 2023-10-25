# American-Express-Customer-Default-Prediction

Overview

Credit default prediction is a critical task in the consumer lending industry. The ability to predict the probability that a customer will not pay back their credit card balance is central to managing risk and optimizing lending decisions. In this project, we aim to develop a machine learning model to predict credit defaults using a dataset provided by American Express.

Objective

The main objective of this task is to predict the probability that a customer will default on their credit card balance in the future based on their monthly customer profile. The target variable is binary and is calculated by observing a performance window of 18 months after the latest credit card statement. If the customer does not pay the due amount within 120 days after their latest statement date, it is considered a default event.

About the Dataset

The dataset used in this task contains aggregated customer profile features for each statement date. These features are anonymized and normalized, and they fall into several general categories:

D_*: Delinquency variables

S_*: Spend variables

P_*: Payment variables

B_*: Balance variables

R_*: Risk variables

Additionally, there are some categorical features in the dataset, including: B_30, B_38, D_63, D_64, D_66, D_68, D_114, D_116, D_117, D_120, and D_126.

In total, there are 190 variables in the dataset. The training set contains approximately 450,000 customers, and the test set contains around 925,000 customers. Due to the dataset's size, a compressed version of the train and test sets is used, which can be obtained from the AMEX-Feather-Dataset.


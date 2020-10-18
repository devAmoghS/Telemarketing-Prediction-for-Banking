# Telemarketing-Prediction-for-Banking

![](https://img.freepik.com/free-vector/call-center-flat-design-illustration_188398-200.jpg?size=626&ext=jpg)

This is an independent Jupyter notebook where we want to predict **whether a customer will buy a term loan or not**

# About the dataset
It is a dataset that describing Portugal bank marketing campaigns results.
Conducted campaigns were based mostly on direct phone calls, offering bank client to place a term deposit.
If after all marketing efforts client had agreed to place deposit - target variable marked `yes`, otherwise `no`

# Tasks
1. Reducing the costs of the marketing teams incurred during campaigns
2. Improving the success rate of the converting the prospect to customer

# Gains Chart and Lorenz Curve

1. `N` is the size of each of my deciles (10% of the original population).
2. `Event Rate` and `Non Event Rate` will add upto 100%.
3. `KS` is the difference between `Cum ECR` and `Cum NECR`. We want to check where it maximizes (yellow shaded cell).
4.  In the `No Model Scenario`, we are taking the standard assumption that **each decile is only contributing to 10% event capture**. This will be useful for the baseline comparision
5.  Hence, we can target the top 2 deciles to capture (Total Event Capture Rate => 46 +18 => 64%).
6.  The maximum discrimantion is achieved in the top 2 deciles but we can also move upto the 3rd decile.

#### If we were to target the top 3 deciles {10, 9, 8} then we would captured 71% compared to 30% in a no model scenario

#### We can also design audience profiles and perform prioritze targeting to improve overall perfomance when compared to random selection of audience

![](https://github.com/devAmoghS/telemarketing-prediction-for-banking/blob/main/Gains%20Chart%20and%20Lorenz%20Curve.png)

#### TODO
1. Audience Profile creation

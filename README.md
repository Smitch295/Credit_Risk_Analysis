# Credit_Risk_Analysis

## Purpose of this anaylsis: 

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company you will use different machine learning models to perform anaylsis of the datasets to see which would be best to predict credit risk.

## Results:

### Naive Random Oversampling: 
![Screen Shot 2022-03-29 at 11 42 46 AM](https://user-images.githubusercontent.com/93875400/160651225-08dc17b9-7026-411a-8873-b52e06d1d3e3.png)
* Balanced accuracy is about 65 % 
* high risk precision is 1% and low_risk is 100%.
* recall precentage is 62% for high risk and 68% for low risk.

### Smote Oversampling: 
![Screen Shot 2022-03-29 at 11 49 01 AM](https://user-images.githubusercontent.com/93875400/160652534-f9c6eeb6-c67c-47c8-b4ec-a0c382f1f0bd.png)
* Balances accuracy score is about 64 %
* high risk precision is 1% and low_risk is 100%.
* recall precentage is 63% for high risk and 66% for low risk.

### Undersampling:
![Screen Shot 2022-03-29 at 12 45 07 PM](https://user-images.githubusercontent.com/93875400/160663377-ff4d299d-7060-4309-b3c1-a069d1da1d66.png)
* Balances accuracy score is about 51 %
* high risk precision is 1% and low_risk is 100%.
* recall precentage is 59% for high risk and 44% for low risk.

### Combination (Over and Under) Sampling:
![Screen Shot 2022-03-29 at 12 47 11 PM](https://user-images.githubusercontent.com/93875400/160663727-7c38d598-1ae3-4da1-b4f1-d0f7d9a4c721.png)
* Balances accuracy score is about 51 %
* high risk precision is 1% and low_risk is 100%.
* recall precentage is 59% for high risk and 44% for low risk.

### Balanced Random Forest Classifier:
![Screen Shot 2022-03-29 at 12 57 48 PM](https://user-images.githubusercontent.com/93875400/160665594-2e26b61c-2ba1-4229-bc8c-ccddf2a12a2d.png)
* Balances accuracy score is about 79 %
* high risk precision is 4% and low_risk is 100%.
* recall precentage is 67% for high risk and 91% for low risk.

### Easy Ensemble AdaBoost Classifier:
![Screen Shot 2022-03-29 at 12 55 27 PM](https://user-images.githubusercontent.com/93875400/160665198-4b9f11f5-99d8-4916-939d-2128350f8b32.png)
* Balances accuracy score is about 93 %
* high risk precision is 7% and low_risk is 100%.
* recall precentage is 91% for high risk and 94% for low risk.

## Summary:

In all the modules, the accuracy of precision for high risk credit loans was low.
In my opionion the best module to use for predicting credit risk because it had to highest percentage for positively identifying low and high risk loans compared to the other modules. 


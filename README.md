# Video Games Sales Analysis


## Credit Risk Analysis Report

### Analysis Overview
The purpose of this Analysis is to find out how reliable money borrowers are on behalf of a lending services company. evaluate a model based on loan risk using various techniques. I've evaluated a model based on loan risk with the dataset of historical lending activity from the previously mentioned company.
My goal is to determine the healthy loans and non-healthly. For this, I used a Logistic Regression tool for my machine learning model since it's the most efficiently used model to identify a target variable.
After I split the original data by training and testing sets, I analyzed the value_counts and determined that the data was imbalanced: Healthy Loans = 75,036 and non-healthy loans = 2,500.
I then analyzed the value_counts again, but this time I split the resampled data. This resulted in a balanced data and the Healthly Loans = 56,271 and non-healthy loans = 56,271.


### Results:
#### Model 1, Logistic Regression Model - Original Data, Imbalanced.
  * The Balanced Accuracy Score of the Model is 0.9520479254722232 which is 95%.
  * The Precision Score for the The Healthy Loan Status is 100%.
  * The Recall Score for the The Healthy Loan Status is 99%.
  * The Precision Score for the The Non-Healthy Loan Status is 85%.
  * The Recall Score for the The Non-Healthy Loan Status is 91%.


#### Model 2, Logistic Regression Model - Resampled Training Data, Balanced.
  * The Balanced Accuracy Score of the Model is 0.9936781215845847 which is 99%.
  * The Precision Score for the The Healthy Loan Status is 100%.
  * The Recall Score for the The Healthy Loan Status is 99%.
  * The Precision Score for the The Non-Healthy Loan Status is 84%.
  * The Recall Score for the The Non-Healthy Loan Status is 99%.


### Summary:
I would make a recommendation to use the resampled model because it performs best. The Balanced Accuracy score of this model was 99% and the data was balanced. This indicates that the model makes lesser mistakes in identifying non-healthy loans. Lastly, this model also gives less false positives.


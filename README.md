# Video Games Sales Analysis


## Introduction
This Project aimed to analyze and visualize Video Games Sales Data using machine learning (ML) amongst other technologies.
We have made predictions on Global Sales for Video Games using Neural Networks and Classical Learning. The Machine learning libraries used were: Scikit-Learn, abcd,. We utilized Tableau to create some visualizations along with Time Series Graphs using Matplotlib.
The dataset used in this project was retrieved from https://www.kaggle.com/datasets/gregorut/videogamesales.




### Analysis
The very first attempt involved using a linear regression which resulted in an extremely low score of 0.15056839384958853. This was due to the dataset not providing enough data for the model to make a prediction on. Moreover, ..

We then utilized Logistic Regression and achieved a higher score of.


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



### Dataset
The data retrieved in the CSV files are from 1980 to 2020. The columns of focus were Platform, Year, Genre, Publisher, NA Sales, EU Sales, JP Sales, and Global Sales.
<p>


### Summary:
I would make a recommendation to use the resampled model because it performs best. The Balanced Accuracy score of this model was 99% and the data was balanced. This indicates that the model makes lesser mistakes in identifying non-healthy loans. Lastly, this model also gives less false positives.


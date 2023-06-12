# Video Games Sales Analysis


## Introduction
This Project aimed to analyze and visualize Video Games Sales Data using machine learning (ML) amongst other technologies. The purpose was to classify whether or not a Video Game would be considered a Hit, which is Sales of $100,000 or higher.
We have made predictions using Neural Networks and Classical Learning. The Machine learning libraries used were: Scikit-Learn, keras-tuner, Matplotlib, Pandas, TensorFlow. We also utilized Tableau to create visualizations along with Time Series Graphs using Matplotlib.



### Analysis
#### Supervised Learning - Regression
The very first attempt involved using a linear regression model which resulted in an extremely low score of 0.151. This may be in part due to the dataset not having enough features for the model to make a prediction on. This was furthur depicted in the Time Series Graphs made.

#### Supervised Learning - Classification



#### Neural Networks - Convolutional Neural Networks


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
The dataset used in this project was retrieved from https://www.kaggle.com/datasets/gregorut/videogamesales.
The data retrieved in the CSV files ranges from 1980 to 2020. The columns of focus were Platform, Year, Genre, Publisher, NA Sales, EU Sales, JP Sales, and Global Sales.
<p>


### Summary:
I would make a recommendation to use the resampled model because it performs best. The Balanced Accuracy score of this model was 99% and the data was balanced. This indicates that the model makes lesser mistakes in identifying non-healthy loans. Lastly, this model also gives less false positives.


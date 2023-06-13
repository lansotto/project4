# Video Games Sales Analysis


## Introduction
This Project aimed to analyze and visualize Video Games Sales Data using machine learning (ML) amongst other technologies. The purpose was to classify whether or not a Video Game would be considered a Hit, which is Sales of $100,000 or higher.
We have made predictions using Neural Networks and Classical Learning. The Machine learning libraries used were: Scikit-Learn, keras-tuner, Matplotlib, Pandas, TensorFlow. We also utilized Tableau to create visualizations along with Time Series Graphs using Matplotlib.


### Dataset
The dataset used in this project was retrieved from https://www.kaggle.com/datasets/gregorut/videogamesales.
![image](https://github.com/lansotto/project4/assets/119235680/6cb994c7-212c-41e8-b610-0ea544754bd3)

The data retrieved in the CSV files ranges from 1980 to 2020. The columns of focus were Platform, Year, Genre, Publisher, and Global Sales.
<p>


### Visualizations
#### Sales by Genre
The graphs below show Game Sales over top 5 Genres.
 ![image](https://github.com/lansotto/project4/assets/119235680/b443bcfe-f757-49fd-b799-361647779f98)
![image](https://github.com/lansotto/project4/assets/119235680/710035c9-52e0-40b2-b1b0-a2df2e19dc52)

 
 #### Time Series
The graph below shows Global Sales of all Genres over time.
 ![image](https://github.com/lansotto/project4/assets/119235680/81c7c852-1f99-4c28-83d9-e6e484ebcab2)


### Analysis
#### Supervised Learning - Regression
The very first attempt involved using a linear regression model which resulted in an extremely low score of **0.151.** This may be in part due to the dataset not having enough features for the model to make a prediction on. This was also depicted in the scatter plot graph below.
 ![image](https://github.com/lansotto/project4/assets/119235680/e6882daa-3ab2-4c65-b733-5fbff1bda293)


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



### Summary:
I would make a recommendation to use the resampled model because it performs best. The Balanced Accuracy score of this model was 99% and the data was balanced. This indicates that the model makes lesser mistakes in identifying non-healthy loans. Lastly, this model also gives less false positives.


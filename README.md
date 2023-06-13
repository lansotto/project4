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
<p>
 
 #### Time Series
The graph below shows Global Sales of all Genres over time.
 ![image](https://github.com/lansotto/project4/assets/119235680/81c7c852-1f99-4c28-83d9-e6e484ebcab2)
<p>

### Analysis
#### Supervised Learning - Regression
The very first attempt involved using a linear regression model which resulted in an extremely low score of **0.151.** This may be in part due to the dataset not having enough features for the model to make a prediction on. This was also depicted in the seaborn pair grid below.
 ![image](https://github.com/lansotto/project4/assets/119235680/e6882daa-3ab2-4c65-b733-5fbff1bda293)


#### Supervised Learning - Classification
The second attempt utilized a logistic regression model. We had the following labels for our hits: **0 = Sales less than $100k, 1 = Sales equal to or more than $100k. **
As shown below, the Imbalanced Model yielded an Accuracy score of **96.2%** wherease the RandomOverSampler Model yielded an Accuracy score of **92.7%**
 
Imbalanced Testing Classification Report  
![image](https://github.com/lansotto/project4/assets/119235680/f37f07c2-9aa0-4f40-854d-745c50dc16b0)
<p>
RandomOverSampler Testing Classification Report  
![image](https://github.com/lansotto/project4/assets/119235680/6ceb60cc-cb4f-4ab0-b024-2a0c1d009eef)
<p>

#### Neural Networks - Convolutional Neural Networks
Lastly, we used Neural Networks to compare traditional vs. deep machine learning. The Best Value Accuracy score is **96.5%.**
 
Hyperparameter Optimization
![image](https://github.com/lansotto/project4/assets/119235680/ebcb7330-bbb9-4eba-96a2-326d2a40604c)

 Results
 ![image](https://github.com/lansotto/project4/assets/119235680/0cd58b49-06c1-4205-890d-6563472aeb13)


### Conclusion:
Based on the performances of our analysis, our recommendation for the best model would be Classification with Logistic Regression. Although Neural Networks yielded a similar score, it required a much longer time to run. Moreover, Neural Networks are more susceptible to overfitting.

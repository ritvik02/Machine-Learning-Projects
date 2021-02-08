# Trained a model to predict weather. Dataset consists of a century of historical averages of global temperatures, including global maximum temperatures, global minimum temperatures, and global land and ocean temperatures. 


## Data Preparation
- made a copy of the dataframe so as not to corrupt the original. After that, we are going to remove the columns that have high cardinality.
High cardinality refers to columns whose values are very rare or unique. Given the frequency of high cardinality data in most time-series datasets, solved this problem directly by completely removing these high cardinality columns from our dataset so as not to confuse our model in the future. 

- Converted columns into DateTime object.


## Visualization and training

- Visualised data to find correlations between the data.

-Separated the data into features and targets. The target, also called Y, is the value we want to predict, in this case, the actual average land and ocean temperature and features are all the columns the model uses to make a prediction.

- Using sckiit-learn split the data into train and test, trained a Random Forest algorithm which is capable of performing both the tasks of classification as well as regression.


## Result
Model learnt to predict weather conditions with an accuracy of 98.02%.


## Objective
The goal is to find out if deep learning can do a pretty good job with tabular data as well. In order do so, we are going to compare its performance against the performance of Random Forests.

We see a lot of tabular data in our daily lives from excel spreadsheets to relational databases to financial reports. Hence, it would be interesting to see if these can be applied to neural nets as well. One advantage of using neural nets over traditional methods is that, with neural nets, feature engineering becomes much more simpler. Although not completely eliminated, there isn’t much of a need to generate new features as there would be with something like Logistic Regression.

the reason for choosing Random Forests for this comparison is that it is quite a robust model when it comes dealing with tabular data. It is robust because it works well for all kinds of applications, usually doesn’t over fit (& easy to stop if it does), doesn’t require a separate validation set, and has very few (if any) assumptions about our data.


## Dataset
The dataset we are dealing with here is a relatively small dataset and good for experimentation. It deals with a bunch of adults and their characteristics and our goal is to predict if the adult’s salary is ≥ 50k or < 50k.


## Process
-	Performed exploratory data analysis and preprocessing before applying ML and DL models.
-	initialized a Random Forest classifier, trained it, tune some hyper-parameters, to make predictions. Observed an accuracy of 86%.
-	Achieved an accuracy of 85% using Deep Learning. 


## Conclusion
An accuracy of 85% using deep learning. So neural nets do perform as well as a hyper tuned Random Forest. The initial skepticism they faced about not being able to work well with training data can be easily banished.


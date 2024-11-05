# classification-challenge

In this challenge we have use two predictive modelling techniques to try to predict if something is spam using our dataset. The file is located in the M_13_starter_code folder, and named spam_detector.ipynb

I predicted that the random forests classifier will perform better than the logistic regression model because this dataset has many features. The random forest classifier's ability to average many different subsets of data should be good for handling a dataframe with many features like this one. My prediction is supported by the accuracy scores calculated using each model.

First  I preprocessed the data into X and y, scaled my data, and used the train_test_split to separate my test and train data.
Then for each model I trained the data using my training data, made a prediction using my test data, and calculated the accuracy score.

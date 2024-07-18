Predicting the Sale Price of Bulldozers using Machine Learning
This machine learning project aims to predict the sale price of bulldozers.

Problem defition How well can the model predict the future sale price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers have been sold for?. This model aims to predict a number, this kind of problem is known as a regression problem.(RandomForestRegressor)

Data Source - Kaggle Bluebook for Bulldozers competition: https://www.kaggle.com/c/bluebook-for-bulldozers/data

There are 3 main datasets:

Train.csv is the training set, which contains data through the end of 2011.

Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.

Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

Evaluation RMSLE (root mean squared log error) between the actual and predicted auction prices.

Note: The goal for most regression evaluation metrics is to minimize the error. For this project the goal is to build a machine learning model which minimises RMSLE.

Features Kaggle provides a data dictionary detailing all of the features of the dataset: https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit?usp=sharing

For more on the evaluation of this project check: https://www.kaggle.com/c/bluebook- for-bulldozers/overview/evaluation

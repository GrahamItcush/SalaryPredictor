# SalaryPredictor
## A machine learning program to predict salaries

This program uses R and a dataset from https://www.kaggle.com/jackogozaly/data-science-and-stem-salaries to predict the salary of some employee at a large tech company based on their education, experience, years at company, etc. Using the tree library, I built a regression tree to generally predict the salary of someone in the field using the tree function. Then I tested the tree using 10-fold cross validation to see if it needed any pruning (it did not), before testing out an input by passing the tree a person and seeing what salary ot would predict.

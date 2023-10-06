# [Task 1](https://github.com/ShinkorenokArina/ITMO_study/blob/9ed4cf07712a76edc2d475c1aa2b43ec225ef07d/ML/Task_1_ShinkorenokArina_Group_J4132c.ipynb)

Description:
1. Train 4 different classifiers using sklearn library to predict "Activity" (biological response of the molecule) field from the "bioresponse.csv" dataset:
- small decision tree;
- deep decision tree;
- random forest on small trees;
- random forest on deep trees;
Split the data to train and test as 75%/25%.

2. Calculate the following metrics to check the quality of your models:
- precision;
- recall;
- accuracy;
- F1-score;
- log-loss;

3. Plot precision-recall and ROC curves for your models.

4. Train a classifier who avoids Type II (False Negative) errors and calculate metrics from p.2 for it. Recall for it should be not less than 0.95.


# [Task 2(3)](https://github.com/ShinkorenokArina/ITMO_study/blob/29874dcfabcfef018d6f285cfdd923f76503b39d/ML/task_2(3)(optimisation_methods)_ShinkorenokArina_Group_J4132c.ipynb)

Description:
1. Develop yourself using numpy library:
a) python function for implementation of gradient descent (GD) with momentum algorithm for the function of two variables f(x,y).
b) python function for implementation of ADAM optimization algorithm for the function of two variables f(x,y).

3. Come up with a function of two variables of an arbitrary form and implement the search for its minimum using those implemented in p.1 functions - a) and b).

5. Illustrate the process of finding an extremum in the form of a graph of the dependence of the value of the difference between two successive approximations of the solution (x_next – x_prev) on the iteration number N or in the form of 2D-plane graph.

6. Write a conclusions about the accuracy of the implemented algorithms.

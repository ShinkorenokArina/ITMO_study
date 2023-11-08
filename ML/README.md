# Laboratory works on the course "Технологии машинного обучения / Machine Learning".

Performed by Arina Shinkorenok (group j4132c)

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

# [Task 2](https://github.com/ShinkorenokArina/ITMO_study/blob/52107da125013bd4e04bb90b4d5af08c14491665/ML/task_2_ShinkorenokArina_Group_J4132c.ipynb)

Description:
1.	Download Alice in Wonderland by Lewis Carroll from Project Gutenberg's website http://www.gutenberg.org/files/11/11-0.txt
2.	Perform any necessary preprocessing on the text, including converting to lower case, removing stop words, numbers / non-alphabetic characters, lemmatization.
3.	Find Top 10 most important (for example, in terms of TF-IDF metric) words from each chapter in the text (not "Alice"); how would you name each chapter according to the identified tokens?
4.	Find the Top 10 most used verbs in sentences with Alice. What does Alice do most often?

# [Task 3](https://github.com/ShinkorenokArina/ITMO_study/blob/b21663b10d2e82b1d904426269236e605544dbeb/ML/task_2(3)(optimisation_methods)_ShinkorenokArina_Group_J4132c.ipynb)

Description:
1. Develop yourself using numpy library:
a) python function for implementation of gradient descent (GD) with momentum algorithm for the function of two variables f(x,y).
b) python function for implementation of ADAM optimization algorithm for the function of two variables f(x,y).

3. Come up with a function of two variables of an arbitrary form and implement the search for its minimum using those implemented in p.1 functions - a) and b).

5. Illustrate the process of finding an extremum in the form of a graph of the dependence of the value of the difference between two successive approximations of the solution (x_next – x_prev) on the iteration number N or in the form of 2D-plane graph.

6. Write a conclusions about the accuracy of the implemented algorithms.


# [Task 4](https://github.com/ShinkorenokArina/ITMO_study/blob/75bdcaf86103619551cf2c73d5009706c543ba8f/ML/task_4_ShinkorenokArina_Group_J4132c.ipynb)

Description:
1.	Apply the logistic regression method using the functions in the notebook «Logistic Regression as a Neural Network – BP alg.ipynb” to predict the biological response of a molecule 
data: bioresponse.csv, 
description from Kaggle: “The data is in the comma separated values (CSV) format. Each row in this data set represents a molecule. The first column contains experimental data describing a real biological response; the molecule was seen to elicit this response (1), or not (0). The remaining columns represent molecular descriptors (d1 through d1776), these are caclulated properties that can capture some of the characteristics of the molecule - for example size, shape, or elemental constitution. The descriptor matrix has been normalized.”). 
Use 75% of the dataset to train the model, and the rest of the data to estimate its accuracy.

2.	Modify optimize() function to implement the stochastic gradient descent (SGD) method and Adam optimization method using the numpy library. Apply them to solve the problem from p.1.

3.	For three modifications of gradient descent (GD, SGD and Adam) plot the learning curves (dependence of the value of the loss function on the iteration number), apply models with different values of the learning rate (at least 5 different learning rates). How does it affect the accuracy of the model? 

4.	Compare the accuracy of the models fitted with various BP algorithms.

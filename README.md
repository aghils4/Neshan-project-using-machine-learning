# Neshan-project-using-machine-learning
Dynamic routing using graphs and software data


This project includes the following files:

# project_notebook.ipynb :

In this file, the main model is built, which predicts the travel time and the shortest route at every moment of the trip based on the available data.
# network.gpickle :

Streets graph file for use in routing
# dataset.csv :

The file required to predict the time of crossing each street, which includes the following columns:

edge_id: Number of each street
length : The size of each street
minute : Time to start moving
speed : Street crossing speed based on other conditions
is_holiday : Holiday or non-holiday day
weather : Weather conditions

# imputed data.ipynb :

Notebook for missing data management by knn method

# data_imp.csv :

Data after fixing the missing ones

# test_cases.csv :

Test data

# test_cases_finall.csv :

Prediction file on test data



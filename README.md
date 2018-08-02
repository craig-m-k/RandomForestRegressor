# RandomForestRegressor

A random forest regressor written in Python with Cython optimizations.

This regressor builds each decision tree in the usual greedy fashion.  Splitting can be done in one of two ways: either using correlation to select the best feature at any given node (which requires the data set to have no missing values), or features can be selected randomly (so the data set can have missing values).

View the notebook [here](https://nbviewer.jupyter.org/github/craig-m-k/RandomForestRegressor/blob/master/Random%20Forest%20Regressor.ipynb).

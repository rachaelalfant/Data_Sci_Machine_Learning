# Linear Regression

__Linear Regression__ is one of the most commonly used techniques in data science and machine learning. Typically, these algorithms seek to minimize the gap between the model's predictions and the training data. 

This directory contains two implementations of linear regression:
 - We train a linear regression algorithm using the Normal Equations and the [LinearRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html) class in Sklearn to find the minimizer for the Mean Squared Error from a dataset generated by Sklearn's [make_regression](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_regression.html#sklearn.datasets.make_regression). 
 - We train a neural network algorithm using Gradient Descent to solve the problem: <img src="https://render.githubusercontent.com/render/math?math=\min_{x \in \mathbb{R}^n} f(x)">, where f(x) is some differentiable function.

--- 

### Software Requirements

The following packages are required to run the attached code:

- [Numpy](https://numpy.org/doc/)
- [Matplotlib.pyplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
- [Sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)

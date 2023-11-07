# Welcome to My Linear Regression
***

## Task
TODO - What is the problem? And where is the challenge?

## Description
Description
Subject
Getting and analysing existing data is the very first task of a data scientist.
The next step is to find tendencies and to generalize.

For example, let's say we want to know what a cat is. We can learn by heart some pictures of cats and then classify as cat animals that are similar to the pictures.
We then need a way to "measure" similarity. This is called instance-based learning.

Another way of generalizing is by creating a model from the existing examples and make prediction based on that model.

For instance, let's say we want to analyze the relation between two attributes and plot one against the other:
We clearly see a trend here, eventhough the data is quite noisy, it looks like the feature 2 goes up linearly as the feature 1 increases.
So in a model selection step, we can decide to go for a linear model.

feature_2 = θ0 + θ1 . feature_1

This model has two parameters, θ0 and θ1. After choosing the right values for them, we can make our model represent a linear function matching the data:

Everything stands in "choosing the right values". The "right values" are those for which our model performs "best".
We then need to define a performance measure (how well the model performs) or a cost function (how bad the model performs).

These kind of problems and models are called Linear Regression.
The goal of this journey is to explore linear and logistic regressions.



## Installation
TODO - How to install your project? npm install? make? make re?

## Usage
python my_linear_regression.py
```
Best theta found is [[1.8228387 ]
 [5.32153953]]
Value of f at this theta: f(theta) = [[3.49169474]]
Value of f prime at this theta: f'(theta) = [[-0.35432261]
 [-1.35692094]]
[1.7, 5.4]
```

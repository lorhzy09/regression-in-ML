---
title: "Introducing Regression Models"
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- What is a Regression Model?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- Explain what a Regression Model is. 
- Recognize a Simple Linear Regression Model. 
- Understand its usages and interpret it in real life context. 

::::::::::::::::::::::::::::::::::::::::::::::::


## What is a "Regression"?

Regression analysis is a core concept in machine learning, specifically supervised learning where our dataset has both input features and output labels. The goal is to determine a relationship amongst variables by analyzing how one affects the others. 

The real life example that we'll work in the lesson is related to movies! Imagine if you are a producer who wants to know the success of a movie before it is released. You have a [dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) of around 5000 films, containing information on their ratings, popularity, etc... 
How can we predict the revenue based on the ratings or popularity of a certain film? Understanding regression models may allow you to answer such questions. 

::::::::::::::::::::::::::::::::::::: keypoints

**Definition**: 
Regression models are mathematical methods that predicts a continuous outcome (usually called y) based on the value of one or more predictor variables (x).

**Motivation**: 
Determine the nature of the relationship between the two numerical variables
and quantify it


::::::::::::::::::::::::::::::::::::: 





## What is an SLR?

The most basic regression model and well-known algorithm is the *Simple Linear Regression Model (SLR)*, which we will focus on in this introductory modual. 

A linear regression line has an equation of the form $Y = \beta_1x + \beta_0 + \epsilon$

$\beta_1$: slope of line

$\beta_0$: intercept

$X$: explanatory variable

$Y$: dependent variable

$\epsilon$: difference between our predicted value from the regression line and the actual vale. 


:::::::::::::::::::::::::::::::::::::: challenge

### SLR in Action? 

Think about a problem in your academic field or everyday life where an SLR  model could help you solve? 

:::::::::::::: solution

### Possible Ideas: 

- Predict film revenue based on their ratings 
- Predict wine price by its date 


:::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::::::::::::::




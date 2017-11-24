# PredictingWages_EnsembleMethods

Python implementation of a case study in Module 2 of the MITProfessionalX course "Data Science: Data to insights".

The case study is: "Module 2 Case Study - Regression and prediction". This case study is about using ensemble methods in R on wages data.

## Points of interest
The analysis is relatively simple (linear regression), but it might be interesting to see how to do it using the two libraries, [sklearn](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html) and [patsy](https://patsy.readthedocs.io/en/latest/#).

---

## Project description

Our goals are:

1) Predict wages using various characteristics of workers.

2) Assess the predictive performance of different methods (linear model, lasso, cross-validated lasso, random forest, Ridge, cross-validated Ridge, Elastic net, cross-validated Elastic net) and combine them using Ensemble method. using adjusted MSE and R^2 , and out-of-sample MSE and R^2.

## The data

Data is from the March Supplement of the U.S. Current Population Survey, year 2012.

* Focus on the single (never married) workers with education levels equal to high-school, some college, or college graduates.

* The sample is of size n ≈ 4,000.

* The outcome Y is hourly wage, and X are various characteristics of workers.

## The notebook
[Linear Regression.ipynb](https://github.com/aless80/PredictingWages_Regression/blob/master/Linear%20Regression.ipynb)

---

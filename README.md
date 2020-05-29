# Project Title
House price prediction using Regression

## Introduction
This is my final project in Machine Learning: Regression. For this project, the code was written to predict the price of a house for sale based on the previous sales data. This code needs to process the avialable data to a useable format and train various regression models to predict the price. Also, for each model Root Mean Sq. Error(RMSE) is calculated to measure the performance of the model.

The following models are used to predict the house prices :-
* **Simple Linear Regression -**  Linear regression performs the task to predict a dependent variable value (y) based on a given independent variable (x). So, this regression technique finds out a linear relationship between x(input) and y(output).
* **Multiple Regression -**  It is an extension of simple linear regression. It is used when we want to predict the value of a variable based on the value of two or more other variables.
* **Ploynomial Regression -**  It is a form of linear regression in which the relationship between the independent variable x(input) and dependent variable y(output) is modeled as an nth degree polynomial. 
* **Random Forest Regression -**  A Random Forest is an ensemble technique capable of performing both regression and classification tasks with the use of multiple decision trees and a technique called Bootstrap Aggregation, known as bagging.
* **LASSO Regression -**  It is a type of regression analysis in which both variable selection and regulization occurs simultaneously. This method uses a penalty which affects they value of coefficients of regression. As penalty increases more coefficients are becomes zero and vice Versa.
* **Nearest Neighbour -** It s a simple, supervised machine learning algorithm that can be used to solve both classification and regression problems. In this nearest house to the query house is searched and according to the price of that house price is predicted.  

## Install
This project requires Python 3. Also, soame of the python libraries like matplotlib, numpy, turicreate, math, etc.
Installed [Anaconda](https://www.anaconda.com/products/individual), a pre-packaged Python distribution that contains most of the necessary libraries and software for this project. 

[Turi Create](https://pypi.org/project/turicreate/) is an open source toolset for creating Core ML models. To install turicreate following command can be used...

```!pip install turicreate ```

## Code
The code contains the foloowing parts-
* ``` Part 1``` Importing the required modules and loading the data set.
* ``` Part 2``` Pre-processing the data to make it usable.
* ``` Part 3``` Implementing various Regression moedls, predicting the house price and calculating RMSE for each model.

## Data
**SFrame** is the data structure for representing tabular data in turicreate. So, the data used for this project is a SFrame
of *House Sales in King County, USA* dataset available on [Kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction)

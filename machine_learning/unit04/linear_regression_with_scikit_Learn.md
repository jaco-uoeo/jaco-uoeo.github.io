# Linear Regression with Scikit-Learn
{: .hidden-title }

## Overview

Linear Regression in Scikit-Learn is a straightforward and widely used technique to understand and model the relationship between variables. It works by finding the best-fitting straight line that predicts a target value based on one or more input features. With Scikit-Learn’s ```LinearRegression()``` class, you can easily train the model using ```.fit(X, y)```, make predictions with ```.predict()```, and measure accuracy using metrics like the R² score. It’s useful for tasks like predicting house prices or fuel efficiency, and fits smoothly into Scikit-Learn’s ecosystem for preprocessing, model evaluation, and building machine learning pipelines.

## Activities

### Tutorial
This activity was about learning how to apply regression techniques using Scikit-Learn. We started by exploring the dataset and creating plots to check for linear patterns between variables. In Demo 2, we walked through the process of building a regression model, beginning with splitting the data into training and testing sets. Using Scikit-Learn’s tools, we trained the model, made predictions, and evaluated its performance. Toward the end, we also looked at nonlinear regression to see how it compares to linear models and when it might be a better fit, depending on the shape and behavior of the data.

The Here's a link to the notebook on colab.

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/ml-artefact/blob/main/Unit04/demo_correlation_regression_fuel_consumption.ipynb)


## Global Population

1. **Task A:** Exploring Correlation
Using the provided datasets (Global_GDP.csv and Global_Population.csv), start by cleaning and preparing the data. Calculate the average population and average per capita GDP for each country over the period 2001–2021, making reasonable adjustments for any missing data. Once processed, investigate whether there is a correlation between the two variables. Create a visual representation of the relationship and offer a brief interpretation of the plot. Also, calculate and comment on the Pearson Correlation Coefficient to quantify the relationship.

2. **Task B:** Applying Regression
Carry out a linear regression analysis where the average population (2001–2021) is used as the independent variable, and the average per capita GDP (2001–2021) is the dependent variable. 

Here's a link to the completed notebook on colab.

[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jaco-uoeo/ml-artefact/blob/main/Unit04/global_population.ipynb)

[Back to Machine Learning](/machine_learning/)
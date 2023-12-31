# Regression Model Selection

This project aims to explore and compare different regression models for predicting a target variable based on a given dataset. Five regression models were considered: Decision Tree Regression, Multiple Linear Regression, Polynomial Regression, Random Forest Regression, and Support Vector Regression. The evaluation results indicate that the Random Forest Regression model performs best for the given dataset. 

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Evaluation](#evaluation)

## Introduction

In this project, we address the problem of regression model selection. Regression models are widely used in various fields to predict continuous target variables based on a set of input features. By comparing different regression models, we aim to identify the most suitable model for our dataset.

## Dataset

The dataset used in this project consists of various features that can potentially influence the energy output of a power plant. The features are as follows:

**AT (Ambient Temperature)**: The ambient temperature

**V (Vacuum)**: The vacuum pressure

**AP (Ambient Pressure)**: The ambient pressure

**RH (Humidity)**: The relative humidity


The target variable is:

**PE (Energy)**: The net hourly electrical energy output of the power plant in megawatts (MW).
The dataset is collected from a power plant and contains measurements of the ambient temperature, vacuum pressure, ambient pressure, humidity, and the corresponding energy output. The goal of this project is to predict the energy output based on the other features.



## Models

In this project, we experimented with the following regression models:

1. Decision Tree Regression: This model uses a decision tree algorithm to predict the target variable. It partitions the feature space into regions and assigns a regression model to each region.

2. Multiple Linear Regression: This model assumes a linear relationship between the target variable and the input features. It estimates the coefficients of the linear equation using the least squares method.

3. Polynomial Regression: This model extends the multiple linear regression by introducing polynomial terms of the input features. It captures non-linear relationships between the variables.

4. Random Forest Regression: This ensemble model combines multiple decision trees to make predictions. It reduces overfitting and improves accuracy by averaging the predictions of individual trees.

5. Support Vector Regression: This model utilizes support vector machines to perform regression. It maps the input features to a higher-dimensional space and finds the hyperplane that best fits the data.

## Evaluation

To select the best regression model for our dataset, we conducted a comprehensive evaluation. The evaluation metrics used were R-squared.

Based on the evaluation results, the Random Forest Regression model outperformed the other models, the R-squared coefficent is 0.96159 . Therefore, we selected the Random Forest Regression model as the best model for our dataset.

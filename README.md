# Support Vector Regression (SVR) for Salary Prediction

This repository contains a Python implementation of Support Vector Regression (SVR) to predict salaries based on job position levels. The model is trained on a dataset containing different job roles, their corresponding levels, and salaries.

## Table of Contents

- [Overview](#overview))
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Overview

Support Vector Regression (SVR) is a type of regression that uses Support Vector Machines (SVMs) to perform non-linear regression tasks. This notebook demonstrates the application of SVR to predict salaries based on position levels.

The key steps include:
- Loading and preprocessing the dataset
- Training the SVR model
- Predicting salaries
- Visualizing the results

## Dataset

The dataset used in this project is `Position_Salaries.csv`. It consists of three columns:
- `Position`: The job title
- `Level`: The corresponding job level
- `Salary`: The salary for each position

Example of the dataset:

| Position         | Level | Salary  |
|------------------|-------|---------|
| Business Analyst | 1     | 45,000  |
| Junior Consultant| 2     | 50,000  |
| Senior Consultant| 3     | 60,000  |
| Manager          | 4     | 80,000  |
| Country Manager  | 5     | 110,000 |

## Results
The SVR model is used to predict the salary for a given job level. The predictions are visualized alongside the actual data points.

## Visualization Example
The following plot shows the predicted salary curve using SVR, with actual salaries displayed as red dots:
The model fits a non-linear curve that captures the trend in salary data.


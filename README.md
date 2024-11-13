# Income Prediction Using Linear Regression

## Overview

This project performs an analysis of the relationship between income and other factors (age and experience) using **linear regression** models. The goal is to predict income based on these variables and evaluate the strength of the relationships. Both simple and multiple linear regression techniques are used to explore how age and experience influence income, and to determine the best model for predicting income.

## Objective

- To understand the relationship between income and two key factors: **age** and **experience**.
- To compute and interpret simple linear regression models for the relationship between income and age, and income and experience.
- To calculate the correlation coefficients to quantify the strength of these relationships.
- To visualize the relationships using scatter plots and regression lines.
- To determine the most appropriate model (simple vs. multiple linear regression) for predicting income.

## Methodology

This project follows these steps:

1. **Simple Linear Regression**: 
   - The relationship between income and age is modeled using a simple linear regression.
   - Similarly, the relationship between income and years of experience is also modeled using simple linear regression.

2. **Correlation Coefficients**:
   - The strength of the relationship between the variables is evaluated using the correlation coefficient (r).
   - Correlation between income and age, income and experience, and age and experience is calculated.

3. **Visualization**:
   - Scatter plots are created to visualize the relationships between age, experience, and income.
   - Regression lines are added to each scatter plot to show the trend.

4. **Multiple Linear Regression**:
   - A multiple linear regression model is used to combine age and experience to predict income.

## Dataset

The dataset used in this project is a CSV file containing the following columns:
- **income**: The income of the individual.
- **age**: The age of the individual.
- **experience**: The number of years of experience.

Make sure to download or place the dataset file `multiple_linear_regression_dataset.csv` in the working directory before running the analysis.


### Required Libraries

This project requires the following R libraries:
- `tidyverse`
- `ggplot2`
- `knitr`

You can install them using the following commands:
```r
install.packages("tidyverse")
install.packages("ggplot2")
install.packages("knitr")

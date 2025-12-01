# Statistical Methods for Data Science 2

## Overview

This project applies Bayesian statistical methods to diabetes prediction using the diabetes dataset. The analysis includes exploratory data analysis and Bayesian logistic regression models implemented with JAGS.

## Project Contents

- `final_project.R` - R script containing the complete analysis
- `final_project.html` - HTML report with analysis outputs and visualizations

## Methods Used

The project follows these main steps:

1. Exploratory Data Analysis (EDA) with visualization of key variables
2. Bayesian logistic regression using JAGS (Just Another Gibbs Sampler)
3. Model comparison between logit and probit link functions
4. Model refinement by removing non-significant covariates

## Dataset

The analysis uses the diabetes dataset which includes variables such as pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, and diabetes outcome.

## How to Run

The R script requires the following libraries:
- ggplot2, gridExtra
- caret, performanceEstimation
- rjags, jagsUI, coda
- scales, reshape2

Run the `final_project.R` script in R or RStudio to reproduce the analysis.

IV Estimation and Simulation in R

📌 Overview

This project demonstrates the simulation and estimation of econometric models in R, focusing on Ordinary Least Squares (OLS) and Two-Stage Least Squares (2SLS) regression. It explores issues of endogeneity and how Instrumental Variables (IV) can be used to obtain consistent estimators.

Features:

- Simulation of Data Generating Process (DGP): Generates synthetic data with endogenous and exogenous variables.
- OLS Estimation: Performs naive OLS regression and visualizes the bias in estimators.
- 2SLS Estimation: Uses IV regression to address endogeneity and estimate consistent parameters.
- Residual Analysis: Plots residuals to assess model performance.
- Estimator Comparison: Compares OLS and 2SLS estimators using density plots and joint visualizations.
- Graphical Outputs: Generates density plots, scatter plots, and fitted regression lines to illustrate key insights.

Installation

Ensure you have R installed. Then, install the required packages by running:

install.packages("AER")
install.packages("tidyverse")
install.packages("mvtnorm")
install.packages("stargazer")
install.packages("jtools")
install.packages("corrplot")

Usage

Open R or RStudio and load the required libraries:

library(tidyverse)
library(AER)
library(mvtnorm)
library(stargazer)
library(jtools)
library(corrplot)

Run the script to generate data, estimate models, and visualize results.

source("script.R")

Example Output 

- OLS vs. 2SLS Estimators Consistency
- Density plots showing estimator bias
- Residual vs. Fitted Values Scatterplots
- Graphs to assess model fit
- Joint Estimator Plot
- Compares OLS and 2SLS fitted values

Files

script.R: Contains the full code for simulation, estimation, and visualization.

README.md: This documentation.

License

This project is open-source under the MIT License.

Acknowledgments

This project is inspired by econometric techniques for dealing with endogeneity in regression models.

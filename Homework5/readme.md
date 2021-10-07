# Sample Regression Analysis

This repository contains a regression analysis of a dataset focused on windmill power generation.
# Dataset Description

The dataset was retrieved from Kaggle.com and contains attributes related to windmills used to generate electricity.
# Business Question/Problem Statement

Be able to estimate power generation based on environmental factors. This would allow engineers to determine the placement and construction of windmills to allow for optimal power generation.
# Exploratory Analysis Findings

We found that the generator temperature had a large negative effect on the power generation, so it might be useful to control for that when the turbine is running.
# Regression Results

40% of our variation was captured with a regression model. One of the biggest issues with this dataset was large unexplained outliers like 1000mph winds which exceeds the world record for wind speen.
# Predictions Using this Dataset

We attempted using a lasso regression but found no benefit compared with the OLS model.
# Potential Next Steps and Follow-ups

It would be beneficial to examine why there were such odd readings with the wind speed, and it might be useful to collect more than just one sample from each windmill.

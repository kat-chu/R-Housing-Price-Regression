# Housing Price Regression Analysis in R

## Overview
This project applies simple and multiple linear regression techniques in R to analyze housing price data. The analysis compares model performance using R², MSE, RMSE, residual plots, QQ plots, and ANOVA, demonstrating a clear improvement when moving from a single predictor to a multi-variable regression model.

## Tools & Libraries
- R / RStudio
- Base R (lm, anova, qqnorm, plot)
- readr

## Key Techniques
- Simple Linear Regression
- Multiple Linear Regression
- Residual Analysis
- QQ Plot Normality Testing
- MSE / RMSE Model Evaluation
- ANOVA Model Comparison
- Categorical Variable Encoding

## Dataset
The dataset contains residential housing records with features including area, number of bedrooms, bathrooms, stories, amenities, and furnishing status.

## Results Summary
| Metric | Simple Regression | Multiple Regression |
|--------|-------------------|---------------------|
| R² | 0.287 | 0.674 |
| RMSE | ~$1,577,613 | ~$1,050,000 |
| MSE | 2.49e+12 | 1.11e+12 |

Adding structural and categorical predictors more than doubled the explanatory power of the model and significantly reduced prediction error.

## File
- `Housing_Price_Regression_Analysis.Rmd` — Full analysis with code, visualizations, and written interpretations

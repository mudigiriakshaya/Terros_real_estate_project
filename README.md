# Terros Real Estate -Housing prices Prediction 
# Multiple Linear Regression Analysis
# Project Overview
This project involves building a Multiple Linear Regression Model to analyze the relationship between various independent variables and a target variable. The model evaluates key predictors and their impact, providing actionable insights for decision-making.

# Dataset
Observations: 506

Features Used: 8 independent variables

Target Variable:  Housing Prices

# Key Performance Metrics
Adjusted R²: 0.69 (indicating that 69% of the variance in the target variable is explained by the predictors)

Standard Error: 5.13 (measuring the average deviation of actual values from predicted values)

F-Statistic: 140.64 (showing strong model significance with a p-value of 1.91E-122)

# Significant Variables and Insights
| Feature   | Coefficient | Impact   | P-Value  | Insight |
|-----------|------------|----------|----------|---------|
| AVG_ROOM | +4.12      | Positive | 3.69E-19 | More rooms increase the target value |
| LSTAT    | -0.61      | Negative | 5.41E-27 | Higher lower-status population reduces target value |
| NOX      | -10.27     | Negative | 0.0085   | Higher pollution levels lower the target value |
| PTRATIO  | -1.07      | Negative | 7.08E-15 | Higher student-teacher ratio negatively impacts the target |
| TAX      | -0.014     | Negative | 0.0002   | Higher taxes slightly reduce the target variable |

# Conclusion
The model effectively identifies key drivers of the target variable.

Features like average room size positively influence the outcome, while pollution levels, lower-status population, and tax rates negatively impact predictions.

The regression model is statistically significant, making it a useful predictive tool for analysis and decision-making.


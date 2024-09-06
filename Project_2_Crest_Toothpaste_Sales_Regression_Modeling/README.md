# Project 2: Crest Toothpaste Sales Regression Modeling

## Report
View report here -
(https://rpubs.com/rahil1998/1217009)

## Overview
This project focuses on determining a regression model for predicting Crest toothpaste’s future sales based on historical advertising budget, advertising ratio, and personal disposable income data collected from 1967 to 1980.

## Objectives
- Develop a regression model to predict Crest’s sales using advertising budget, advertising ratio, and personal disposable income.
- Evaluate and compare the full model with a reduced model to determine the most significant predictors.
- Assess model performance using AIC, BIC, F-statistic, R-squared, Adjusted R-squared, and Mallow’s Cp statistics.

## Data Description
- **Data Source**: Proctor and Gamble Crest toothpaste sales data.
- **Columns**:
  - Crest Budget: Crest’s advertising budget.
  - Ratio: Crest’s advertising budget as a proportion of Colgate’s advertising budget.
  - Income: Personal disposable income.
  - Sales: Crest’s sales (response variable).
- **Observations**: Data from 1967 to 1980.

## Methodology
- **Data Preparation**: Filtered and cleaned data for analysis.
- **Model Building**: Fitted and compared a full regression model with three predictors (Crest Budget, Ratio, Income) and a reduced model with only one predictor (Income).
- **Evaluation Metrics**: AIC, BIC, F-statistic, R-squared, Adjusted R-squared, and Mallow’s Cp.

## Results
The reduced model (using only Income) was selected as the most significant model with a p-value of 1.268e-09 for the model and 1.27e-09 for the Income variable. Residual analysis confirmed that all model assumptions were satisfied.

## Future Directions
- **Forecasting**: Generate forecasts using the selected model to predict future sales of Crest toothpaste.

## How to Use
- **Setup**: Requires R and necessary packages.
- **Usage**: Run `Regression Analysis Project 2.Rmd` in RStudio to generate the analysis report.

## Files
- `README.md`: This file.
- `Regression Analysis Project 2.Rmd`: The R Markdown file with code and analysis.
- `Regression-Analysis-Project-2.html`: The HTML report of the analysis.

## License
This project is licensed under the MIT License.

## Contact
For more information, please contact [Mohammad Rahil](mailto:smrahil98@gmail.com).

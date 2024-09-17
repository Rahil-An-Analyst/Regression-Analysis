# Project 1: King County House Sales Price Prediction

## Report
View report here -  
(https://rpubs.com/rahil1998/1217006)

## Overview
This project aims to develop and evaluate multiple regression models to predict house prices in King County, Washington, using filtered public records of home sales from May 2014 to May 2015.

## Objectives
- Build a suitable regression model to predict house prices using selected predictors.
- Perform model selection and evaluation using various regression techniques.
- Assess model performance and provide a detailed conclusion on the best-fitting model.

## Data Description
- **Data Source**: Kaggle (2016) and GeoDa (2020) - King County house sales records.
- **Filtered Columns**:
  - **price**: Price of the house sold (response variable)
  - **bedrooms**: Number of bedrooms
  - **bathrooms**: Number of bathrooms
  - **sqft_living**: Square footage of living space
  - **sqft_lot**: Square footage of the lot
  - **floors**: Number of floors
- **Filtered Observations**: 4,385 house sales records from May 2014 to May 2015.

## Methodology
- **Descriptive Analysis**: Initial exploration of the filtered data to understand the distribution of variables.
- **Model Building**: Four models were built and compared:
  1. Linear Regression Model (Log-transformed response)
  2. Logistic Regression Model (Odds of getting low-priced house)
  3. Poisson Regression Model (Count of houses per price range)
  4. GLM Regression Model (Gamma-distributed response with log link)
- **Evaluation Metrics**: Model significance, assumptions, and fit statistics like AIC, Deviance, and R-squared.

## Results
The best model identified is the Generalized Linear Model (GLM) with a gamma-distributed response and log link, best capturing the right-skewed price distribution.

## How to Use
- **Setup**: Requires R and relevant packages (`stats`, `MASS`).
- **Usage**: Run `RegressionProject1.Rmd` in RStudio to generate the full analysis report. Ensure you download and update the location of the `kc_house_data.csv` in the Rmd before running.

## Files
- `README.md`: This file.
- `RegressionProject1.Rmd`: The R Markdown file containing code and analysis.
- `RegressionProject1.html`: HTML report of the analysis.
- `kc_house_data.csv`: The filtered dataset used for modeling.

## License
This project is licensed under the MIT License.

## Contact
For more information, please contact [Mohammad Rahil](mailto:smrahil98@gmail.com).

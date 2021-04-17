# Project 2 - Ames Housing Data and Kaggle Challenge

**Problem Statement**

I have clients who want to invest in houses either by selling or buying.  They want to know what features are going to most influence the price of the house.  The information I am presenting should help them to make an informed decision.
The goal of this project is to help my clients find a desired house for a decent price by building a regression model that will best predict the sale price.  The data I use is from Ames Housing Spreadsheet

### Executive Summary

This analysis will take the following steps to generate predictions of home prices:

- Systematically clean and transform data features
- Conduct exploratory analysis, in order to understand the relationships between variables, and their wider implications on housing market value
- Build and fit a predictive model, based on a curated group of features from this data set, that can be used on unseen housing data to accurately predict sale prices

### Insights

This report concludes that the following elements have the greatest impact on the potential sale price of a home:

- QverallQual
- YearBuilt
- TotalBsmtSF
- GrLivArea
- FullBath

### Modeling
The main notebook begins by importing and cleaning a training data set of 2051 homes with 80 different features. Once cleaned, I examined the extent of the correlation between each feature as well as to SalePrice, our target variable and identified main features for the model I built.
Besides the EDA analysis, I have performed log transformation and also generated RMSE and R2 scores for all three models.  The data listed below:

#### for RMSE comparisons:
- rmse = 33612.327986636046
- rmse_ridge = 35277.752341545456
- rmse_lasso = 34051.57325362071

#### for R2 Score comparisons:
- (0.7870948662958206, 0.7905485853922427) for linear regression
- (0.7867968596811882, 0.7881703836747072) for Ridge
- (0.7862851949031171, 0.7880428585438313 for Lasso

**Conclusion and Recommendations**

I have identified what features are the best predictors of housing price.  I have addressed missing data and outliers and improved my model by Ridge and Lasso.  I finally have created a regression model and was able to generate new data to predict sale price.  Now I can recommend the following to my clients:

- Invest in a house with a large living area  
- Invest in a house that has good overall quality
- Invest in a house that was built recently
- Invest in a house that has more full bath rooms
- Invest in a house with higher basement square footage

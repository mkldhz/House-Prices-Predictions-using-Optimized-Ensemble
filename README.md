# House Prices Predictions using Optimized Ensemble
This is a complete solution of the "House Prices - Advanced Regression Techniques" competition in Kaggle. The data set has 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. 
## Goal
The aim of the competiton is to predict with some a ccuracy the price of each house depending on it features.
## Metric
The Competiton submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted value and the logarithm of the observed sales price. 
## Feature Explination
The data set contains 79 features, here is a breif explination for some of them:
* SalePrice: the property's sale price in dollars. This is the target variable that you're trying to predict.
* MSSubClass: The building class.
* MSZoning: The general zoning classification.
* LotFrontage: Linear feet of street connected to property.
* LotArea: Lot size in square feet.
* Street: Type of road access.
* Alley: Type of alley access.
## Using Ensemble for Predictions
The model used is a Regression Ensemble model that contains 4 sub-models. 
Those models were the best performing models, that were combined to form the Ensemble model, that utilizes all of them to make a prediction about the price of a house.
The 4 sub-models are:
* Support Vector Regression
* Ridge Regression
* LGBM Regressor
* Bagging Regressor

## Conclusion
A RMSE Score of 0.12448 was achieved by the model.

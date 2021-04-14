# housepriceprediction

## Introduction:

The basic definition of the problem is to predict the prices of the houses based on the features given. The project revolves around predicting the price of the house depending on the features given. A dataset has been given which has the features of houses and its prices for the year 2014-2015. The dataset has 21 columns, which could all be used as variables. All possible variables will be evaluated in order to decide if they are contributing to the algorithm. For example, the number of square meters/feet will probably have a more direct relation to the price as opposed to the amount of trees in the yard.

The algorithm will predict the price for a house based on one or more predictors like date, zip code, square footage, number of bathrooms. It will be supervised and as a response the prices will be used. The end goal of the algorithm is that someone can put in several features of a house and the algorithm will estimate for how much it probably will be sold. Since the output is quantitative, a regression method will be used to make the prediction.

## Data:

The dataset that is going to be used for this project is obtained from Kaggle. It contains the house prices of King County in Washington and includes Seattle. The data is publicly available and contains 21 columns and 21613 rows. This dataset was chosen because of the amount of observations and the large amount of variables. The data ranges between May 2014 and May 2015. A training and test set will be produced from the data in order to train and test the algorithm. Since the problem is a regression problem, several regression methods will be considered. These are: Linear Regression, Polynomial Regression, Ridge Regression, Stepwise Regression and Lasso Regression. To find the best algorithm for the problem, these will be tested and their performance will be evaluated. The best one will be chosen thereafter.

## Installation: 

* R-Studio
* R-tools

## R-packages (dependencies):
* knitr
* pander
* glmnet




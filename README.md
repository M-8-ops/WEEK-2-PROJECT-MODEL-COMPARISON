# WEEK-2-PROJECT-MODEL-COMPARISON
Let's say we want to build a model to predict booking prices on Airbnb. Between Linear Regression and Random Forest Regression which model would perform better and why?
SOLUTION:
First we have generated data on mackaroo containing Airbnb prices in 3 cities. WE have proceeded to clean the data,perform data-preprocessing then built the respective models
We have used the same data to build a random forest regression model
We have used the same data to build a multiple linear regression model
We have then selected the best model for predicting the Airbnb prices by using the R-Squared metric.
DEspite negative R-Squared values obtained for both cases due to a combination of factors such as overfitting,or many outliers as is the case with generated data:
the random forest regression model had a higher R-Squared value hence performed better at predicting the Airbnb prices.
Random forest regression analysis is therefore highly recommended for handling similar problems.

# W1_Market-Price-and-Direction-Prediction
Uses linear regression to predict closing price and time series, along with XGBoost to predict direction. I've used the GC=F (Gold) stock.
The data has been imported from the yfinance module. You can swap gold for any other stock if required.
The models themselves are relatively poor, with the linear regression achieving an R^2 score of -0.00010334972008396726 and the direction predictor yielding a mean accuracy of 0.5051.
Modules used:
* Yahoo! Finance
* Scikit
* Matplot
* Numpy
* XGBoost

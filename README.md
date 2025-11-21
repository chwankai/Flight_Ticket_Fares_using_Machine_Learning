# Flight Ticket Fares Prediction using ML
This project focuses on the domain of flight ticket price prediction, where the pricing is often influenced by factors such as flight duration, seat availability, airline, travel dates, and booking conditions. Three models including Linear Regression, KNN Regression, and Random Forest Regression were used in this study.

## Dataset Source
https://www.kaggle.com/datasets/justinmitchel/flightprices-min?resource=download

## Accuracy Analysis
### Linear Regression
R2 Score	0.6307 / 63.07%
MAE	63.84
MSE	7899.51
RMSE	88.88
### KNN Regression
R2 Score	0.8341 / 83.41%
MAE	20.11
MSE	3548.68
RMSE	59.57
Best Hyperparameters	Weight = "Uniform", p = "1", n_neighbours = "1"
### Random Forest Regression
R2 Score	0.8722 / 87.22%
MAE	29.15
MSE	2735.10
RMSE	52.30
Best Hyperparameters	n = "100", min_split = "10", min_leaf ="1", max_ features = "sqrt", max_depth ="40"

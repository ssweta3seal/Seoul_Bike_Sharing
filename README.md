# Seoul_Bike_Sharing
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

Tags: Imputter, One-hot Encoder, StandardScalar, Linear Regression, Random Forest, Decision
tree, XGBoost, VIF, GridsearchCV, Hyperparameter Tuning RMSE, R-square, Feature Importance.

1. Predicting bike-sharing demand can help companies to allocate their services better and ensure more sufficient circulation of bikes for customers. 
2. Developed hyper-parameter tuned gradient Boosting to predict the number of bikes that can be rented per hour by the company. 
3. Implemented different ML algorithms Linear Regression, DT, RF, SVM, and XGBoost, to predict the Bike count per hour. Imputed missing values, encoded categorical features, handled outliers, and checked multicollinearity. 
4. The same modeling technique can be used for Transportation, E-Commerce, and TaxiDemand Prediction.
This project will be explored over the previous data in order to predict the number of bikes that can be rented per hour by the company. So that customers can get the best experience without any delays. We will build different regression models and check which proves to be the best for the deployment.

Project Flowchart:
* Loading data and Diagnosing the data
* Data Filtering
* EDA of Row data to understand inside correlations
* Feature Engineering
* Feature Selection
* Model Building
* Model Training and Testing
* Model Evaluation & Hyper Parameter tuning

Models Used
* Linear Regression
* Lasso Regression
* Ridge Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* XGBoost

Conclusions:

- Bike rental count is mostly correlated with the time of the day as it is peak at 8 am morning and 6 pm in the evening.
- We observed that the bike rental count is high during working days than on non-working days.
- We see that people generally prefer to bike at moderate to high temperatures and when little windy.

# Python_Car_Price_Prediction
https://www.kaggle.com/competitions/busa-competition 

Group project for BUSA8001 unit, in which I covered task 3: Fitting and tuning Linear Regression, Gradient Boosting, Random Forest model to choose the best model.
Objective: Forecast the price of used cars based on the training dataset which includes 8,000 entries with 37 variables, to predict for the testing dataset includes 4,000 observations of 36 variables. The target variable is the price of the car. 
Method: By tuning the hyperparameters via cross-validation and evaluate model predictive performance using Mean Absolute Percentage Error (MAPE) indicator, we choosed the best model among Linear Regression, Gradient Boosting, Random Forest model. In cross-validation, we create Parameters grid to find the best parameter for each model. With each model's optimized parameter, we evaluate each model based on MAPE score. 
Result: Random Forest was the best model and was used to predict the final predictions.

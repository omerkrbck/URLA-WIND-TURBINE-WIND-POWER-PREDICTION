# URLA-WIND-TURBINE-WIND-POWER-PREDICTION
A 12 month data were collected from ERA5 and active power values of wind turbines were taken from EPIAS Transparency Platform in order to predict the Urla wind turbines' wind power.

In order to develop an application that utilizes historical wind speed, wind direction and temperature values, and machine learning algorithms to forecast wind turbine power output. It’s a regression problem. After analysing and understanding the dataset, a model can be built to predict wind turbine power production by using the hourly wind speed, wind direction and temperature. Machine learning algorithms were used such as Regressors Models (KNeighbors Regressor, Decision Tree Regressor, Extra Trees Regressor, Gradient Boosting Regressor and Random Forest Regressor) and Long Short-Term Memory (LSTM).

In order to do this, import the necessary libraries like Sckitlearn, tensorflow library for models, pandas, numpy, seaborn, matplotlib for data and visualization.

First define X (inputs) variables as hourly wind speed, wind direction and temperature; and y (output) variable as wind power. Then split dataset into train and test datasets. Enter test size as 0,3. Then fit the models and evaluate our models’ success with evaluation metrics such as MSE, RMSE, MAE, R-squred.

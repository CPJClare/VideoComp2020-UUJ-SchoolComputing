# VideoComp2020-UUJ-SchoolComputing
"Training regret minimisation charts for STP (nu = 3) dEI outperforming GP dEI"

The training regret’s inter-quartile range (IQR)  for STP dEI (green shading) is lower than the IQR for GP dEI (yellow shading) for each of the 4 synthethic functions e.g. Rosenborck, Hartmann3, Levy, Sum Squares [1] and the real-world problem [2] e.g. tuning 6 hyperparameters for XGBoost Regression [3] to predict New York City taxi fares.

Additionally, the root of Mean Squared Error (RMSE) is lower for STP (nu = 3) dEI (versus GP dEI) on the test data’s predictions [2].

[1] https://www.sfu.ca/~ssurjano/optimization.html

[2] https://www.kaggle.com/c/new-york-city-taxi-fare-prediction

[3] https://xgboost.readthedocs.io/en/latest/python/index.html

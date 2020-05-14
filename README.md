# Forecast-Daily-Interstate-94-Westbound-Traffic-Volume-for-MN-DoT-ATR-Station-301
Time series forecasting project using SAS

The purpose of this project is to forecast daily Interstate 94 Westbound traffic volume for MN DoT ATR station 301, roughly midway between Minneapolis and St Paul, MN. We also want to assess the effect of days of the week, Holidays, and different weather conditions on traffic.Study results can be used to generate strategies, such as increasing tolls on specific weekdays, to alleviate traffic jams and help reduce car emissions. 

We used SAS Forecasting system and SAS code to develop univariate deterministic time series models (Seasonal Dummies, Seasonal Dummies with error model, Cyclical trend model, Cyclical trend model with error model), univariate stochastic time series models (seasonal ARIMA), and multivariate models (transfer function models).
Predictors in TF models are Average temperature, Amount of rain, and Average percentage of cloud cover. The best performing model (seasonal dummies with Holiday dummy and AR(1) error model) achieves a test MAPE of 14.462.

Some interesting findings: 1) Traffic volume is affected by the Average temprature of 6 days before; 2) Friday is the busiest day of the week; 3) Holidays are less busy than non-holidays.

Models: Seasonal Dummies, Cyclical trend model, Error model, seasonal ARIMA, TF model.







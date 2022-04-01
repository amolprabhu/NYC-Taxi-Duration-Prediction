# NYC-Taxi-Duration-Prediction

# New York City Taxi Trip Time Prediction

This project aims to predict New York city taxi trip times.

The dataset consists of 1458644 rows and 11 columns, containing features such as trip longitude and latitude values, day, month, year of the trip, etc.

The project is executed in 4 main steps:
1. Data cleaning and feature engineering
2. Exploratory data analysis
3. Model building and evaluation
4. Model tuning.

Features such as speed and distance are engineered, to create useful variables. Using latitude and longitude values the area of New York was focused on. 

Exploratory data analysis (EDA) was performed, both univariate and bivariate analysis were done to gain better understanding about the data.
Some understanding from the data was received such as, single passenger trips are the highest, March is the busiest month, Saturday is the busiest day,
trips mostly range to 2000 seconds, highest average speed during the day is at 5 AM, etc.

Models experimented with:
1. Decision Tree
2. Random Forest
3. Gradient Boost
4. XGBoost

Random Forest perfomed best after hyperparameter tuning.

Root Mean Squared Error (RMSE) is chosen as the metric. The metric showed an RMSE of 221 seconds in predictions of trip time.

Improvement of 68% or reduction in deviation of time prediction by 8 minutes compared to the prediction deviations from the mean.

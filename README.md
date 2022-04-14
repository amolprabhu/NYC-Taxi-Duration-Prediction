<h1 align="center"> New York City Taxi Trip Time Prediction </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

## 📋 Summary 
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

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2 id="credits"> :scroll: Credits</h2>

Amol Prabhu | Avid Learner | Data Scientist | Machine Learning Enthusiast

<p> <i> Contact me for Data Science Project Collaborations</i></p>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amolprabhu/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amolprabhu)
[![Medium Badge](https://img.shields.io/badge/Medium-1DA1F2?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@amolprabhu)
[![Resume Badge](https://img.shields.io/badge/resume-0077B5?style=for-the-badge&logo=resume&logoColor=white)](https://drive.google.com/drive/folders/1IL3WB6ONxBI5Zrb3yLZCTydTdSAw9RpS?usp=sharing)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## 📚References
1. Haversine Distance - https://www.igismap.com/haversine-formula-calculate-geographic-distance-earth/
2. NYC boundaries - https://gist.github.com/jakebathman/719e8416191ba14bb6e700fc2d5fccc5
3. Random Forest Regressor - https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

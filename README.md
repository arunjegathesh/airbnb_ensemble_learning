# Airbnb Price Prediction in NYC 
Predicting prices of properties in NYC using ensemble learning methods based on the following Kaggle challenge - https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data

Context

Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present more unique, personalized way of experiencing the world. This dataset describes the listing activity and metrics in NYC, NY for 2019.

Content

This data file includes all needed information to find out more about hosts, geographical availability, necessary metrics to make predictions and draw conclusions.

Acknowledgements

This public dataset is part of Airbnb, and the original source can be found on this website - http://insideairbnb.com.

Inspiration

What can we learn about different hosts and areas?
What can we learn from predictions? (ex: locations, prices, reviews, etc)
Which hosts are the busiest and why?
Is there any noticeable difference of traffic among different areas and what could be the reason for it?

Process Overview

- EDA of the source data
- Transformation of the numerical variables
- Missing value & outlier treatment
- Regression Model 
  - RandomForestRegressor
  - XGBoostRegressor
  - CatBoostRegressor
- Feature Importance
- Evaluation

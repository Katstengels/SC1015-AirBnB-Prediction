# AirBnB Price Predictor

## Contributor
1. Khansa Putri Nugraha (U2320572K)
2. Odilia Kathleen Gunawan (U2321163G)

## About
In this SC1015 project, we analysed AirBnB data from https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data/data and applied machine learning to make prediction based on the given information.


## [Data Extraction](data-extraction.ipynb)
We aim to predict the price of a given AirBnB in New York. To do this, we cleaned the dataset by removing duplicates and invalid inputs. From the cleaned data, we calculated a few new variables that could help us in our future analysis:
- distance_from_center
- room_type_encoded
- neighbourhood_group_encoded
- booking_density
- availability_ratio


## [Data Visualisation](data-visualization-EDA.ipynb)
With the cleaned and improved dataset, we visualised them trough various graphs and diagrams. Through that, we found correlation between the given data of AirBnB specifications and its price. Hence, choosing the most relevant predictors to predict their respective prices.

The predictors that we use are:
- minimum_nights
- number_of_reviews
- reviews_per_month               
- calculated_host_listings_count  
- availability_365                
- distance_from_center            
- room_type_encoded                 
- neighbourhood_group_encoded      
- booking_density                
- availability_ratio


## [Machine Learning](machine-learning.ipynb)
We split the data into train and test sets. With the train set, we initiated machine learning with the XGBoost Gradient Boosting Machine and the random forest regression model. With our models completed, we tested our model with the test set and analysed the accuracy of it's prediction.


## What did we learn?
- The importance of data cleaning to prevent an inaccurate or invalid production
- There is a need to consider data types when choosing a model to use
- How to make use of various models to predict price

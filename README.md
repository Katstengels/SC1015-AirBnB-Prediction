# AirBnB Price Predictor

## Contributor
1. Khansa Putri Nugraha (U2320572K)
2. Odilia Kathleen Gunawan (U2321163G)

## About
In this SC1015 project, we analysed AirBnB data from [New York City Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data/data) and applied machine learning to make prediction based on the given information.

In face of the recent economic crisis, it has become crucial for us as consummers to be able to make smart economic decisions. However, it is not always so easy to determine the worth of an item. For instance, patrons of AirBnB has expressed their confusion over the fluctuating price of AirBnB units as they are often unable to find a clear distinction between units that they deem cheap, moderate, and expensive. Hence, we wanted to analyse the details of these units and see how they affect their prices. With what we have learnt, we then would like to try to predict prices of other AirBnB in the area to see if they are worth the price compared to others. 


## [Data Extraction](data-extraction.ipynb)
We aim to predict the price of a given AirBnB in New York. To do this, we cleaned the dataset by removing duplicates and invalid inputs. From the cleaned data, we conducted data engineering to calculate a few new variables that could help us in our future analysis.

The new variables are:
- distance_from_center
- room_type_encoded
- neighbourhood_group_encoded
- booking_density
- availability_ratio


## [Data Visualisation](data-visualization-EDA.ipynb)
With the cleaned and improved dataset, we visualised them through various graphs, diagrams, and an [interactive map](interactive-map.ipynb). Through that, we found correlation between the given data of AirBnB specifications and its price. Hence, choosing the most relevant predictors to predict their respective prices.

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

## References:
- <https://www.askpython.com/python/examples/mape-mean-absolute-percentage-error>
- <https://stats.stackexchange.com/questions/142873/how-to-determine-the-accuracy-of-regression-which-measure-should-be-used>
- <https://www.kaggle.com/code/faridaelhusseinyy/ml-project-final#Data-cleaning>

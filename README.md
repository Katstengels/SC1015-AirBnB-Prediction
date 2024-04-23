# AirBnB Price Predictor

## Contributor
1. @khansaputri28
2. @katstengels

## About
In this SC1015 project, we analysed AirBnB data from and applied machine learning based on the given data

## [Data Extraction]
We aim to predict the price of a given AirBnB. To do this, we cleaned the dataset by removing duplicates and invalid inputs, visualised the data through various graphs and diagrams, then found correlation between the given data of AirBnB specifications and its price to find the most relevant predictors to predict their respective prices.
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

Then, we split the data into train and test sets. With the train set, we initiated machine learning with the XGBoost Gradient Boosting Machine and the random forest regression model. With our models completed, we tested our model with the test set and analysed the accuracy of it's prediction.

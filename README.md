# Predicting-the-Prices-of-Airbnb-in-New-York
Predicting the prices of an Airbnb With a Tensorflow  NN 


The solution will seek to determine the prices of Airbnbs based on several factors. A model will be build to predict the price of an Airbnb correctly

## The Metric for Success

We aim to establish the price of an Airbnb based on factors such as location, the rooms, the reviews among others. We will do so by using the dataset with Neural Network with Tensor Flow that will corrrectly predict the price of apartments and make reccomendations to both owners and clients on pricing. We seek to realize a precision of 80%.

## The Experimental Design

Below are the steps taken in this analysis

1. loading the required libraries
2. Loading and previewing data
3. Cleaning the data
4. Univariate analysis
5. Bivariate analysis
6. Implementing the solution by using Tensor Flow
7. Challenging the solution and giving insights on how improvements can be made.

## Data Relevance and Validation

The data available is relevant for the intended analysis. It contains information that is significant to predicting the prices of Airbnb based on the various features of rooms in New York in 2019. The data will help us in answering the data analytic question on determining the price of an Airbnb based on the different features.

## Understanding the context

The data set we are to work with contains the following columns:

1. id:Airbnb's unique identifier for the listing
2. name:Name of the listing
3. host_id:Airbnb's unique identifier for the host/user
4. host_name:Name of the host. Usually just the first name(s).
5. neighbourhood_group:The neighbourhood group as geocoded using the latitude and longitude against neighborhoods as defined by open or public digital shapefiles.
6. neighbourhood:The neighbourhood as geocoded using the latitude and longitude against neighborhoods as defined by open or public digital shapefiles.
7. latitude:Uses the World Geodetic System (WGS84) projection for latitude and longitude.
8. longitude:Uses the World Geodetic System (WGS84) projection for latitude and longitude.
9. room_type:"Entire home/apt,Private room,Shared room
10. price:daily price in local currency. Note, $ sign may be used despite locale
11. minimum_nights:minimum number of night stay for the listing (calendar rules may be different)
12. number_of_reviews:The number of reviews the listing has (in the last 30 days)
13. last_review:The date of the last/newest review
14. reviews_per_month:The number of reviews the listing has over the lifetime of the listing
15. calculated_host_listings_count:The number of listings the host has in the current scrape, in the city/region geography.
16. availability_365:avaliability_x. The availability of the listing x days in the future as determined by the calendar. Note a listing may be available because it has been booked by a guest or blocked by the host.

The data used in this analytic can be accessed on kaggle or the csv in this repo



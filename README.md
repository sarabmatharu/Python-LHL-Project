# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Project goals are to use API for citybike, Foursqaure & Yelp. With Citybikes API provides bike sharing data.
CityBikes supports more than 400 cities. 

Your tasks are as follows:

Explore the structure of the API, query the API and understand the data returned.
Choose a city covered by the CityBikes API and retrieve all available bike stations in that city.
For each bike station, use the API to call the latitude, longitude and number of bikes.
Parse the JSON object into a Pandas dataframe.
Complete the city_bikes.ipynb notebook to demonstrate how you executed the tasks above.

To find data through API calls using diffrent conditons and filters, using City Bikes, Foursquare & Yelp API. 

## Process
### (your step 1) - 
First step in the project is to import all required libraries to get requited functionality needed. Go through API documentation to be familiar with APIs. In this projetc we are working with city bikes, Foursqaure & Yelp by making API calls. Step 1 is to explore the structure of the APIs, query the APIs and understand the data returned. Understand data using diffrent functions. Then data was put in a data frame. This is done for all citybike, Foursqaure & Yelp. 

### (your step 2) - 
We can extract diffrent pieces of information requitred as per need & put all that into a dataframe. Then next step is to combine both data frames & see infromation. Eg. from citybike extract information about bikes & from foursquare or yelp extract infromation about point of intrests eg. select a bike station & then find restaurants in the area around bike station. Box plot is used as part of EDA.
All results were put in a sqlite3 database. SQL queires were used to add & extract information from tables. 

## Results
With diffrent API calls to City Bikes, Yelp & Foursquare we can extract data & put in data frame. We supplied diffrent conditions with API calls. And also used regression model. We built a regression model to check compatibilty.

## Challenges 
It was difficlut & time consuming to work with Yelp for some reason. Data parsing also took lots of time. 

## Future Goals
I will be using more conditions to get variety of data. 

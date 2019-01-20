# AirbnbBostonData
What can we learn from AirBnB Boston data?

The project is mainly about data investigation of AirBnB Boston Data. 

The data is from Kaggle page : https://www.kaggle.com/airbnb/boston

The libraries used in the work: 
pandas, numpy and sklearn

The data comes in 3 seperate files; listings, calendar and reviews. listings 
gives each listed home in Boston with some features like description, price, 
amenities, etc. calendar gives information about each listed home each day 
during one year from September 2016 to September 2017. reviews gives reviews,
id of the home reviewed about and date. 

The related questions that are tried to be answered are as follow:

1. How does the price change in Boston during a year? What is the busiest time?
By how much does the price increase at this time?

2. How does price dynamics differ among neighbourhoods?

3. What factors do determine the price of the homes? 

4. How description,summary parts of the listings differ among neghbourhoods? 
What are the most distinctive words used in description, summary special to 
neighbourhoods?

The files included here are:

EDA -- jupyter notebook, includes exploratoy data analysis,data cleaning and 
wrangling parts, visualizations, data wrangling for machine learning, machine
learning parts to look at the deterinants of price and to find the 10 words 
special to each neighbourhood, and finally word cloud.

reviews, calendar, listings, final -- csv files, all data for the analysis. 
final.csv includes the cleaned data

.ipynb_checkpoints -- checkpoints created in Anaconda

.png files -- saved visualizations

For cleaning and data wrangling efforts, machine learning models applied take
a look at EDA.ipynb

summary of the results









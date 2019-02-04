# AirBnB Boston Data


#### Table of Contents

1. [Installation](#Installation)
2. [Project Motivation](#ProjectMotivation)
3. [Data and File Descriptions](#FileDescription)
4. [Results](#Results)
5. [Licensing, Authors and Acknowledgements](#Licensing)

###  Installation
<a name="installation"></a>

The libraries used in the work: 
 - pandas
 - NumPy 
 - scikit-learn


### Project Motivation
<a name="ProjectMotivation"></a>

The project is mainly about data investigation of AirBnB Boston Data and applying
machine learning models to predict price of homes

The related questions that are tried to be answered are as follow:

1. How does the price change in Boston during a year? What is the busiest time?
By how much does the price increase at this time?

2. How does price dynamics differ among neighbourhoods?

3. What factors do determine the price of the homes? 

4. How description,summary parts of the listings differ among neghbourhoods? 
What are the most distinctive words used in description, summary special to 
neighbourhoods?



### Data and File Description
<a name="FileDescription"></a>

The data is from Kaggle page : https://www.kaggle.com/airbnb/boston


The data comes in 3 seperate files; listings, calendar and reviews. 

listings.csv -  each listed home in Boston with some features like description,
price, amenities, etc. 

calendar.csv - information about each listed home each day during one year from September 2016 to September 2017. 

reviews.csv -  reviews, id of the home reviewed about and date. 


The files included here are:

EDA.ipynb -- Anaconda Jupyter Notebook, includes exploratoy data analysis,data cleaning and 
wrangling parts, visualizations, data wrangling for machine learning, machine
learning parts to look at the deterinants of price and to find the 10 words 
special to each neighbourhood, and finally word cloud.

final.csv -- includes the cleaned data

.ipynb_checkpoints -- checkpoints created in Anaconda

.png files -- saved visualizations

For cleaning and data wrangling efforts, machine learning models applied in 
the analysis, take a look at EDA.ipynb


### Results
<a name="Results"></a>


Results from this analysis can be summarized as follows:

1. The average price of homes in Boston is weekly seasonal. Removing this, the 
price decreases drastically from September 2016 until February 2017 by 30%. 
It starts to increase in February, jumps by 14% in mid-April and continues 
increasing until September. 

2. The busiest time in Boston starts in May and continues until September

3. Price movements in each neighbourhood is different.

4. We can predict the price with rmse of $1.51 by using AdaBoostRegressor

5. The variation in price can be explained by features of how many people home
accommodates, latitude and longitude of the place, if rented place is entire 
home/apartment and if the place has a kitchen or not. 

6. The distinctive words used in place description and reviews for each
neighbourhood are found, see EDA.ipynb

7. Word Cloud of reviews reveal that most frequent words are positive about the
experience with AirBnB homes in Boston


You can reach the blog post "What can we learn from AirBnB Boston data?" from 
https://medium.com/@ilknur.chakir/what-can-we-learn-from-airbnb-boston-data-3ac27621bad3


### Licensing, Authors and Acknowledgements
<a name="Licensing"></a>

MIT License









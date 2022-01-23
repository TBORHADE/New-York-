# Airbnb_New-York_2019
Udacity Data Scientist Nanodegree Project

Analysis on 2019 NYC Airbnb Data ([check Medium post]())

## Installation
This project uses the following Python libraries under Python version 4.6:

  Pandas 
  Numpy 
  Matplotlib 
  Seaborn 
  Scikit-learn

Clone this repo to your local machine using `https://github.com/TBORHADE/New-York-.git`. 

## Project Motivation
This project analyzes 2019 NYC Airbnb data to explore the differences in price and availability among different area groups in NYC, to identify the busiest hosts in NYC, and to build up a preliminary linear regression model to predict the listing price of each listing, Reviews, avaibility and top airbnb. 

## File Descriptions
The database used in this project is, originally from [Kaggle](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data).

Python Jupyter, used for coding in this project.

## Interactions
### Findings
#### Area Differences
Mahattan and Brooklyn are two areas that are the most popular among the five boroughs in NYC. Within these two areas, private room and entire home/apartment are the most popular room types. Mahattan has the greatest listing price among the five cities and entire home/apartment are most loved by visitors. 

#### The Most Successful Hosts
In my analysis, I calculate the average revenue for each host in NYC by multiplying the number of days their rooms booked with the list price and averaging this to each listing if the host has more than one listing. The majority of these most successful hosts have listed their rooms in Manhattan and Brooklyn as entire home/apartment

#### The Price Prediction
Based on price distribution of neighbourhood and different types of rooms we can identify that shared rooms are cheaper and entire apartment are most expensive depending on the neighbourhood.  

## Author
Github: https://github.com/Luna-github
## License
Usage is provided under the MIT License. See LICENSE for the full details.

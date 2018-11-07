# ADM Homework 2 - Group #17
# How do Taxis move in NYC?

The final goal of the task is to analyze the Taxi's trips in NYC.

## Get data to analyze
### Download datasets 
The data in usage are available on [NYC Taxi & Limousine Commission](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml) page. 
We use the data for the first six month of 2018, only for the Yellow cabs. The yellow taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. 
We download this dataset, then in order to do the analysis by borough we combine the Yellow cabs data with the dataset found in `taxi_zone_lookup.csv`. 

### Additional data
To understand the data, we read the [legend](http://www.nyc.gov/html/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf) for each column of the data.

To better understand the taxi's trips, we read something about Yellow Taxis in NYC [here](http://www.nyc.gov/html/tlc/downloads/pdf/taxi_information.pdf). 


## Script descriptions
1. `Homework2.py`:
> This script provides the code of the entire analysis. It is divided in two parts:
> 1. the first with the code of *Exploratory Data Analysis*
> 2. the second with the code of *Core Research Questions*.

# ADM Homework 2 - Group #17
# How do Taxis move in NYC?

The final goal of the task is to analyze the Taxi's trips in NYC.

## Get data to analyze
### Download dataset 
The data in usage are available on [NYC Taxi & Limousine Commission](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml) page. 
We used the data for the first six months of 2018, only for the Yellow cabs. The yellow taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

For reference regarding the taxi zones and NY's boroughs, the information can be found in this file `taxi_zone_lookup.csv`. 

### Additional data
To understand the data, we read the [legend](http://www.nyc.gov/html/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf) for each column of the data.

For better understanding of the taxis' trips, we have read information about Yellow Taxis in NYC [here](http://www.nyc.gov/html/tlc/downloads/pdf/taxi_information.pdf). 

#### Remark: 
We have trouble viewing the maps in the Jupyter Notebook Viewer, so we upload the `html` files seperately.

## Script description
1. `Homework_2.ipynb`:
> This script provides the code of the entire analysis. It is divided in two parts:
> 1. the first with the code of *Exploratory Data Analysis*
> 2. the second with the code of *Core Research Questions*.

2. `nyc1.html`
3. `nyc_samelocation1.html`
> They contain the maps of *Core Research Question 2*.

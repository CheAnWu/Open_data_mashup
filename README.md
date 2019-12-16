# Open_data_mashup
This is the final project for the course Open Data Mashup

## A final single dataset file
File1 Name: Airbnb_NBA.csv

File2 Name: Rideshare_NBA.csv

I seperated the final dataset into two files since I want to analyze all the sharing economy, one dataset for Airbnb and another dataset for rideshare service. I think it's reasonable to seperate these two kinds of sharing economy service into two datasets and that's why I provided two final datasets. Moreover, these two datasets both contain a large amount of data and the Jupyter Notebook always kill the kernel when I'm trying to join them together.

## Intermediate datasets

##### Airbnb datasets: 
1. calender.csv
2. listings.csv
3. reviews.csv

##### Rideshare datasets:
Main dataset: Transportation-Network-Providers-Trips.csv 

* It's about 13 gigabytes, which is very insane, so I splitted it into 15 datasets, and it's called "rideshare-output-X.csv", X from 1 to 15.
* After I splitted the dataset into 15 sub datasets, it's still too big for doing the analysis, so I splitted one of the sub datasets into 20 datasets, and each of them contain 150,000 rows of data.

1. Dataset after 1st split: rideshare-output-X.csv. X from 1 to 15
2. Dataset after 2nd split: sub-rideshare-X.csv. X from 1 to 20
3. Datatset for the Jupyter Notebook data analysis: sub-rideshare-1.csv

##### NBA Schedule dataset:
ChicagoBulls-schedule-1819.csv


## Documentation for all datasets
##### Airbnb datasets: 
1. calender.csv: Chicago-Airbnb-calender.md
2. listings.csv: Chicago-Airbnb-list.md
3. reviews.csv: Chicago-Airbnb-review.md

##### Rideshare datasets:
sub-rideshare-1.csv: Transportation-Network-Providers-Trips.md

##### NBA Schedule dataset:
ChicagoBulls-schedule-1819.csv: CHI-201819-schedule.md

##### Final output dataset:
Airbnb_NBA.csv: Airbnb-final.md

Rideshare_NBA.csv: Rideshare-final.md


## Commented and documented code
####File Name: split_tripdata.py
A python file that I used to split the original rideshare dataset.

## Jupyter Notebook
#### File Name: Final-output.ipynb

## Github repo
https://github.com/CheAnWu/Open_data_mashup

## Project entry
#### File Name: project_entry.pdf


## Single summary slide
#### File Name: summary.pdf


## Assessment report
#### File Name: assessment_report.pdf


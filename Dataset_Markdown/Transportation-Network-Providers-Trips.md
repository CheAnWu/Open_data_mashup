
# Data cleaning assessment
- Cleaning nees for this file:
	Use Pandas to load the csv file into a Dataframe. The csv file contains 101 million rows and 21 columns (attributes), and each row of the dataset represents a rideshare trip. I will also use Pandas for data cleaning, dropping the column I don't need, and store the selected columns into a new Pandas dataframe. The columns I may select: Trip Start Timestamp, Trip End Timestamp, Trip Seconds, Trip Miles, Trip Total, Pickup Centroid Latitude, Pickup Centroid Longitude, Dropoff Centroid Latitude, Dropoff Centroid Longitude.
- The amount of time I expect to spend on the process for this file: 2 weeks. Since it's the largest dataset among all of my datasets, it's 12G and it has 101 milllion records, I may only select 40 days that Chicago Bulls had home game and other 40 days not didn't have NBA game. Moreover, I may need more time to split the dataset into maybe 5 sub datasets.


# Description of the authorship, attribution, and/or the provenance of the file.  

The data is provided by City of Chicago - Chicago Department of Business Affairs & Consumer Protection.


# Description of the semantic contents of the file.

The "Transportation Network Providers - Trips" dataset contains all rideshare trips from November 2018 to present, reported by rideshare companies (Uber and Lyft) to the City of Chicago as part of routine reporting required by ordinance.


# Description of the collection process.

Full collection procedure are described on the Chicago Data Portal website. Just click on "Export" and download the csv file.


# Description of the data structure

The data file is in CSV format. There are 101 million rows and 21 columns in the dataset, each row of the dataset represents a rideshare trip in Chicago.

Data types in the dataset (21 columns):

1. Trip ID - Plain text. 
	* A unique identifier for the trip.
2. Trip Start Timestamp - Date & Time. 
	* When the trip started, rounded to the nearest 15 minutes.
3. Trip End Timestamp - Date & Time
	* When the trip ended, rounded to the nearest 15 minutes.
4. Trip Seconds - Integer
	* Time of the trip in seconds.
5. Trip Miles - Integer
	* Distance of the trip in miles.
6. Pickup Census Tract - Plain text
	* The Census Tract where the trip began.This column often will be blank for locations outside Chicago.
7. Dropoff Census Tract - Plain text
	* The Census Tract where the trip ended. This column often will be blank for locations outside Chicago.
8. Pickup Community Area - Integer
	* The Community Area where the trip began. This column will be blank for locations outside Chicago.
9. Dropoff Community Area - Integer
	* The Community Area where the trip ended. This column will be blank for locations outside Chicago.
10. Fare - Integer
	* The fare for the trip, rounded to the nearest $2.50.
11. Tip - Integer
	* The tip for the trip, rounded to the nearest $1.00. Cash tips will not be recorded.
12. Additional Charges - Integer
	* The taxes, fees, and any other charges for the trip.
13. Trip Total - Integer
	* Total cost of the trip. This is calculated as the total of the previous columns, including rounding. 
14. Shared Trip Authorized - Checkbox
	* Whether the customer agreed to a shared trip with another customer, regardless of whether the customer was actually matched for a shared trip.
15. Trips pooled - Integer
	* If customers were matched for a shared trip, how many trips, including this one, were pooled. All customer trips from the time the vehicle was empty until it was empty again contribute to this count, even if some customers were never present in the vehicle at the same time. Each trip making up the overall shared trip will have a separate record in this dataset, with the same value in this column.
16. Pickup Centroid Latitude - Integer
	* The latitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
17. Pickup Centroid Longitude - Integer
	* The longitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
18. Pickup Centroid Location - Location point
	* The location of the center of the pickup census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
19. Dropoff Centroid Latitude - Integer
	* The latitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
20. Dropoff Centroid Longitude - Integer
	* The longitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
21. Dropoff Centroid Location - Locatioin point
	* The location of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.

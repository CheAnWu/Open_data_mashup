# Description of the authorship, attribution, and/or the provenance of the file.  

The data is provided by Inside Airbnb site, and the data behind the Inside Airbnb site is sourced from publicly available information from the Airbnb site.


# Description of the semantic contents of the file.

The "Chicago_Airbnb_review" dataset contains customer review information of all the registered Airbnb in the Great Chicago Area, the most important part of this dataset is that it contains the "date" information of the customer review.

# Description of the collection process.

Full collection procedure are described on the Inside Airbnb website. Just search for the specific location (I searched for Chicago) and then download the "reviews.csv" file from the website.


# Description of the data structure

The data file is in CSV format and each row of the dataset represents an Airbnb review information in Chicago

Selected Data types in the dataset - 3 columns :

1. id — Integer
	* identification number for review
2. listing_id — Integer
	* identification number for listing which we can join with the above DataFrame
3. date — Datetime
	* date of the review

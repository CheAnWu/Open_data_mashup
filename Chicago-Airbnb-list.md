
#Data cleaning assessment
- Cleaning nees for this file:
	Use Pandas to load the csv file into a Dataframe. The csv file contains 8852 rows and 106 columns (attributes), and each row of the dataset represents an Airbnb information in Chicago. I will also use Pandas for data cleaning, dropping the columns I don't need, there're 106 columns in the original dataset and I won't use most of them in the project, so I need to drop them from the dataframe. Then I'll store the selected columns into a new Pandas dataframe.
	- The amount of time I expect to spend on the process for this file: 1 week. Since the dataset is not that large comparing with the Chicago rideshare dataset, but it still need some time for data cleaning since it has 106 columns, so I need to take a look at every column and see if they can add insights to the project or not.

#Description of the authorship, attribution, and/or the provenance of the file.  

The data is provided by Inside Airbnb site, and the data behind the Inside Airbnb site is sourced from publicly available information from the Airbnb site.


#Description of the semantic contents of the file.

The "Chicago_Airbnb_list" dataset contains all the registered Airbnb information in the Great Chicago Area, it contains the name, the review, the space, the description, the price, and all the public information you can find on the Airbnb website when you search for Airbnb in Chicago.


#Description of the collection process.

Full collection procedure are described on the Inside Airbnb website. Just search for the specific location (I searched for Chicago) and then download the "listings.csv" file from the website.


#Description of the data structure

The data file is in CSV format. There are 8852 rows and 106 columns in the dataset, each row of the dataset represents an Airbnb information in Chicago

Selected Data types in the dataset - 12 columns  (Original - 106 columns):

1. id - Integer
	* ID for each Airbnb record.
1. Name - Plain text
	* Name of the Airbnb.
2. Neighborhood_overview - Plain text
	* Description provided by the Airbnb host about the neighborhood. It will have missing value if the hosts didn't provide neighborhood information for their Airbnb. The missing value is a blank in the csv file.
3. Transit - Plain text
	* The transportation information around the Airbnb provided by the host. It will have missing value if the hosts didn't provide transportation information for their Airbnb. The missing value is a blank in the csv file.
4. Zipcode - Integer
	* The zipcode of the Airbnb.
5. Latitude - Integer
	* The latitdue of the Airbnb.
6. Longitude - Integer
	* The longitude of the Airbnb.
7. Property_type - Categorical
	* The property type of the Airbnb, it's a categorical data, including Apartment, Condominium, Boutique hotel, Guest suite, House, Townhouse, Bungalow, Loft, Bed and breakfast, Camper/RV.
8. Accommodation - Integer
	* The accommodation column shows how many people can the Airbnb accommodate (# of people).
9. Price - Integer
	* Price of the Airbnb.
10. Cleaning_fee - Integer
	* Cleaning fee of the Airbnb.
11. Minimum_night - Integer
	* Miminum night the customers have to stay in the Airbnb.
12. Number_of_reviews - Integer
	* Number of reviews for the Airbnb.
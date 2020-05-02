<h1>Airbnb Data Cleaning in Python</h1>

<h3>The Dataset</h3>
The dataset to be used is a CSV file named airbnb.csv, which contains data on airbnb listings in the state of New York. 
It contains the following columns:

•	**listing_id:** The unique identifier for a listing<br/>
•	**description:** The description used on the listing<br/>
•	**host_id:** Unique identifier for a host<br/>
•	**host_name:** Name of host<br/>
•	**neighbourhood_full:** Name of boroughs and neighbourhoods<br/>
•	**coordinates:** Coordinates of listing (latitude, longitude)<br/>
•	**Listing added:** Date of added listing<br/>
•	**room_type:** Type of room<br/>
•	**rating:** Rating from 0 to 5.<br/>
•	**price:** Price per night for listing<br/>
•	**number_of_reviews:** Amount of reviews received.<br/>
•	**last_review:** Date of last review<br/>
•	**reviews_per_month:** Number of reviews per month<br/>
•	**availability_365:** Number of days available per year<br/>
•	**Number of stays:** Total number of stays thus far<br/>

<h3>To do list</h3>
Some issues with the dataset which have been taken care of are:
<h4>Data type problems:</h4>
•	Task 1: Split coordinates into 2 columns and convert them to float<br/>
•	Task 2: Remove $ from price and convert it to float<br/>
•	Task 3: Convert listing_added and last_review to datetime<br/>

<h4>Text/categorical data problems:</h4>
•	Task 4: We need to collapse room_type into correct categories<br/>
•	Task 5: Divide neighbourhood_full into 2 columns and making sure they are clean<br/>

<h4>Data range problems:</h4>
•	Task 6: Make sure we set the correct maximum for rating column out of range values<br/>

<h4>Dealing with missing data:</h4>
•	Task 7: Understand the type of missingness, and deal with the missing data in most of the remaining columns.<br/>



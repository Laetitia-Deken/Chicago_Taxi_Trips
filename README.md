# Chicago_Taxi_Trips Exploratory (In French)
Exploration of Chicago Taxi Trips since 2013 (with Python and SQL - In French)

![Chicago Taxi Trips Exploratory](taxi.jpg "Chicago Taxi Trips Exploratory")

## Links
https://data.cityofchicago.org/stories/s/spcw-brbq

This dataset was kindly made publically available by the City of Chicago at: https://data.cityofchicago.org/Transportation/Taxi-Trips/wrvz-psew

Dataset Chicago Taxi Trips in BigQuery : https://cloud.google.com/bigquery/public-data?hl=fr --> BigQuery hosts the full version of this dataset, which extends from 2013 through the present.

Link to my Dashboard in Looker Studio : https://lookerstudio.google.com/reporting/e28b90f7-9558-42d1-8fe3-d2b766bbfa93

## Context

Context Taxicabs in Chicago, Illinois, are operated by private companies and licensed by the city. There are about seven thousand licensed cabs operating within the city limits. Licenses are obtained through the purchase or lease of a taxi medallion which is then affixed to the top right hood of the car. 
Source: https://en.wikipedia.org/wiki/Taxicabs_of_the_United_States#Chicago 

## Content

This dataset includes taxi trips from 2013 to the present, reported to the City of Chicago in its role as a regulatory agency. To protect privacy but allow for aggregate analyses, the Taxi ID is consistent for any given taxi medallion number but does not show the number, Census Tracts are suppressed in some cases, and times are rounded to the nearest 15 minutes. Due to the data reporting process, not all trips are reported but the City believes that most are. For more information about this dataset and how it was created, see this post  on the City of Chicago's blog.

This public dataset is hosted in Google BigQuery and is included in BigQuery's 1TB/mo of free tier processing. This means that each user receives 1TB of free BigQuery processing every month, which can be used to run queries on this public dataset. Watch this short video to learn how to get started quickly using BigQuery to access public datasets. 

Project completed in September-October 2023.

- unique_key - Unique identifier for the trip.  
- taxi_id - A unique identifier for the taxi.  
- trip_start_timestamp - When the trip started, rounded to the nearest 15 minutes.  
- trip_end_timestamp - When the trip ended, rounded to the nearest 15 minutes.  
- trip_seconds - Time of the trip in seconds.  
- trip_miles - Distance of the trip in miles.  
- pickup_census_tract - The Census Tract where the trip began. For privacy, this Census Tract  is not shown for some trips.  
- dropoff_census_tract - The Census Tract where the trip ended. For privacy, this Census Tract  is not shown for some trips.  
- pickup_community_area - The Community Area where the trip began.  
- dropoff_community_area - The Community Area where the trip ended.  
- fare - The fare for the trip.  
- tips - The tip for the trip. Cash tips generally will not be recorded.  
- tolls - The tolls for the trip. 
- extras - Extra charges for the trip.  
- trip_total - Total cost of the trip, the total of the fare, tips, tolls, and extras.  
- payment_type - Type of payment for the trip.  
- company - The taxi company.  
- pickup_latitude - The latitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy.  
- pickup_longitude - The longitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy.  
- pickup_location - The location of the center of the pickup census tract or the community area if the census tract has been hidden for privacy.  
dropoff_latitude - The latitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy.  
dropoff_longitude - The longitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy.  
dropoff_location - The location of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy. 




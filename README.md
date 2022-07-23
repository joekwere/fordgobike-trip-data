# Part I - (201902-fordgobike-tripdata.csv)
## by (John Ekwere)


## Dataset
> The dataset contains 183412 rows and 16 columns with some missing data. The dataset has about 183,412 rides. The average of the rides is approximately 726 seconds while the maximum and minimum rides are 85,444 and 61 seconds respectively. The features that will help support my investigation are user_type, member_gender, member_birth_year and duration_sec. 

>The following data wrangling steps were used to further clean the data.
> rows with missing data were dropped.
> incorrect data type for start and end time columns were changed to datetime datatype
> id columns were changed to object datatype as well.
> member_birth_year was also changed from float to int
> data type for user_type, member_gender and bike_share_for_all_trip were changed to category datatype



## Summary of Findings

> From my exploration, these were my findings:
Observation 1: The age with the mode of users is around 35 and most of the users are between 30 and 40
Observation 2: From the visualisation, males use the bike trips more
Observation 3: From the visuals, more subscribers tend to use the bike trips than customers
Observation 4: From the visuals, most people prefer not to share bikes on their trip.
Observation 5: From the visuals, MARKET ST AT 10TH ST is the most used Ford Gobike station with 2.1% and 3649 rides, followed by SAN FRANCISCO CALTRAIN STATION 2 with 1.9% and 3408 rides.
Observation 6: From the visuals we can see that San Francisco Clatrain Station 2 is where people alighted the most followed by Market St at 10th St. This also shows that people are mostly moving between these 2 stations as they are the 2 most used stations with regards to both start and end stations.
Observation 7: From the visuals we can see that the least 5 stations amount to 0% which is quite negligible
Observation 8: From the visuals, we can see that the 5 least end stations also contributed 0%.
Observation 9: most trips were around 400 seconds. Most trips were at slightly greater than 400 seconds using a log scale.
Observation 10: From the visuals, most trips across all genders were just around 500. While most males made rides of 1500 and less, others and females made much longer trips.
Observation 11: We can see that customers made more bike trips than subscribers. The plot also shows that q1 for customers is slightly higher than that mean of subscribers.
Observation 12: Females made longer trips than males and others
Observation 13: From the visuals we can see that most trips were done by bikers between 20 and 60. Also, the older bikers did not engage in long distance. The longest trips were done by bikers between the ages of 20 and 50. Most of the trips were also done in less than 10,000 seconds.
Observation 14: Males make up 50% of customers and 70% of subscribers
Observation 15: From the visuals we can see that trip duration for other gender was mostly below 2000 while that of female was between 0 and 4000 although it decreases with age. The trip duration for male also decreased with age. I also observed that males took longer trips. Males between 70 and 80 also had a good number of trips compared to female and other gender.
Observation 16: From the visuals we can see that customers "other customers" make the longest trip duration. male and female subscribers took the shortest trips.
Observation 17: We can see that females have the lowest mean age for both types of users followed by males.


## Key Insights for Presentation

> Trip duration: From the visuals we can see that most trips were done by bikers between 20 and 60. Also, the older bikers did not engage in long distance. The longest trips were done by bikers between the ages of 20 and 60. Most of the trips were also done in less than 10,000 seconds.
> User type distribution: Customers took longer trips than subscribers. The average for customers was over 500 while that of subscribers was less than 500.
> Age and gender by trip duration: Most trip duration for other gender was mostly below 2000 while that of female was between 0 and 4000 although it decreases with age. The trip duration for male also decreased with age. I also observed that males took more trips. Males between 70 and 80 also had a good number of trips compared to female and other gender.

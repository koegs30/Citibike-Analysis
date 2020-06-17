# Citi Bike Analysis

The objective for this project was to find two "phenomena" in the publicly available Citi Bike data (https://www.citibikenyc.com/system-data).  The Tableau file for this project can be found here: https://public.tableau.com/profile/katherine.sullivan#!/

Please note, I have two stories within the tableau file as well as several dashboards and charts.  One story addresses an anomaly with regards the the birth year of renters and the other a look at the type of trip (roundtrip vs end-to-end) and related conclusions.

Stories:
1) Customer Input Birth Year Issue 
Upon initially examination of the Citi Bike data the below graph of renters by birth year was developed.  This graph shows an usual spike in renters reporting to be born in 1969.  This anomaly did not exist in 2014 but does appear in 2018 and 2019.  The story 'BirthYearInputIssue" in the Tableau file examines this issue and poses possible causes and solutions.
![alt text](https://github.com/koegs30/Citibike-Analysis/blob/master/Images/BirthYearGraph3yrs.png)

2) Types of Rentals: Roundtrips and Trips Over 24 Hours
This analysis finds the Citi bike stations with the most roundtrip rentals as well as those stations that initiate the longest rentals.  Stations near parks and along the water (e.g. Central Park, the Brooklyn Bridge, Governor's Island, Prospect Park) appear the generate the most roundtrip rentals.  The location of these starting points coupled with the nature of a roundtrip suggest these are likely sight-seeing / leisure trips versus commuter trips.  This is supported by the relatively few number of roundtrip bike rentals originating at stations in more residential areas like the boroughs outside of Manhattan and those not near / in a park.  This trend is consistent in the month of July in years 2014, 2018 and 2019.
![alt_text](https://github.com/koegs30/Citibike-Analysis/blob/master/Images/RoundTrips.png)

Stations initiating the rentals with the longest durations reveal some interesting trends.  The map below highlights the stations with the longest average durations per bike rental over a layer of household income (pink to green; lowest to highest).  A quick look indicates that the longest trips originate at stations on the edge of the Citi Bike service area and along the edges of low income districts.  This story within the tableau file discusses possible uses of the bikes as well as explanations for the long rental durations.
![alt_text](https://github.com/koegs30/Citibike-Analysis/blob/master/Images/DurationIncome.png)



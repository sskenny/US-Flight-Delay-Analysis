# US Flight Delay Analysis
## Summary 
We analyzed a data set of delayed flights from 2008 in the U.S. to determine the factors which contribute to delays. Among the factors inverstigated were individual airlines, total number of flights, time of day, month of year and airport. We were unable to perform further analysis on the reasons for delay because there were many missing values for the flight delay reason columns. 

## Insights

1. Count of All Flights vs. Delayed Flights: It is apparent from the graph of all flights vs delayed flights that there is a correlation between the two, as was expected. Surprisingly, the volatility in the delayed curve not present in the all-flights curve indicates that delayed flights is not a perfect function of the total number of flights. For example, the variance (or increases and decreases) in the delayed curve between weeks 10 and 20, 50 and 52 and to a lesser extent 36 and 40, is not reciprocated in the all-flights curve.

2. Average Airline Delay Time: The major airline carriers, US Airways, United Airlines, and Southwest Airlines appear to have limited carrier-caused delay times on average. Conversely, all the carrier who shoulder the blame for the longest extended wait times are smaller airlines like Hawaii, Comair, and Atlantic Southeast. Lastly, Mesa Airlines is clearly the worst airline for those fliers who lack patience or loose schedules.


<p align="center">
  <img src="https://github.com/SaritaIngu/US-FlightDelayAnalysis/blob/master/Flight%20Delay%20Images/AvgAirline%20CarrierDelays.png" title="Average Airline Delay Time">
</p>

3.  Airline Percent Flights Delayed: Unlike the average carrier delay times, the major airlines have the highest percentag of flights delayed. Interestingly, contrary to their laid-back image, the airlines representing Hawaii boast the most punctual departures of any carrier.

4.  Percentage of Flights Delayed by Hour and Day: The heat map - Days Of Week + Time of Day, indicates that afternoons and evenings are relatively more delayed compared to mornings. Friday and Sunday evenings are at the peak of delays.
<p align="center">
   <img src= "https://github.com/sskenny/US-Flight-Delay-Analysis/blob/master/images/FlightDelaysbyDayHour.png"
title="Flight Delays By Day and Hour">
</p>

5. Percentage of Flights Delayed by Month: light delays are maximum in the around holiday season. During Christmas and Thanksgiving, the delays could go up to 57%
We have some outliers in the middle of February and end of March, where there are no holidays or any reason that stands out.

4. Delays by Airport: The bubble map showed that the airports with most amount of delays are ATL in Atlanta and ORD in Chicago. ATL had 131,613 delays which constitutes 31.75% of all flights from ATL. ORD had 125,979 delays which constitutes 35.95% of all flights from ORD. Some airports with a lower amount of delays had a higher percentage of delayed flights. For example, AKN in King Salmon had 72 delays which constitutes 62.07% of all flights from AKN.



## Data sets
Delayed US flights in 2008: https://www.kaggle.com/giovamata/airlinedelaycauses
All US flights in 2008:  https://www.kaggle.com/vikalpdongre/us-flights-data-2008#2008.csv
Airport longitude and latitude location: https://raw.githubusercontent.com/jpatokal/openflights/master/data/airports.dat

## Tools And Libraries Used
1. Jupyter Notebook
2. Seaborn, Plotly, pyplot

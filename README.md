# US-Flight-Delay-Analysis

## Summary 
We analyzed a data set of delayed flights from 2008 in the US to find which airports perform the worst in terms of flight delays and we also looked at the best and worst times to travel. We couldn't do analysis on the reasons for delay because there were many missing values for the flight delay reason columns. 

## Insights

1. The bubble map showed that the airports with most amount of delays are ATL in Atlanta and ORD in Chicago. ATL had 131,613 delays which constitutes 31.75% of all flights from ATL. ORD had 125,979 delays which constitutes 35.95% of all flights from ORD. Some airports with a lower amount of delays had a higher percentage of delayed flights. For example, AKN in King Salmon had 72 delays which constitutes 62.07% of all flights from AKN.

2. The heat map - Days Of Week + Time of Day, indicates that afternoons and evenings are relatively more delayed compared to mornings. Friday and Sunday evenings are at the peak of delays.

## Data sets
Delayed US flights in 2008: https://www.kaggle.com/giovamata/airlinedelaycauses
All US flights in 2008:  https://www.kaggle.com/vikalpdongre/us-flights-data-2008#2008.csv
Airport longitude and latitude location: https://raw.githubusercontent.com/jpatokal/openflights/master/data/airports.dat

## Tools And Libraries Used
1. Jupyter Notebook
2. Seaborn, Plotly, pyplot, matplotlib

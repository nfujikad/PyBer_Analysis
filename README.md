# PyBer_Analysis

## Project Overview
The goal is to summarize the ride share data by city type: Urban, Suburban, and Rural. To help visualize the data we will be creating a multiple-line graph showing the total eekly fares for each city type. 

## Resources
-   Data source: city_data.csv, ride_data.csv
-   Software: Python 3.9.12 

## Results

The summary data shows a relationship between city population and total number of rides, which in turn correlates to the number of rides, total fares, and total drivers. Deep in the city you will have more riders leading to more drivers. Assuming, inner city rides are shorter distance and demand is high, this drives prices down. However, as you distance yourself further from the city we see the total number of drivers, rides, and fare sum decrease. The lower demand and need for rides leads to higher prices. 

Ride Share Summary 
![Ride Share Summary ](https://github.com/nfujikad/PyBer_Analysis/blob/main/Resources/Summary.png)

The multiple-line graph shows that all three cities seem to follow a similar trend in regards to total fare per the 5 month span. It would be interesting if the graph was entended past 5 months and conducted for a whole to see how the summer and winter months are. Entering May for suburban drives we see a sharp increase. Perhaps during summer months when kids are home from school ride shares increase. 

Multiple-Line Graph
![Multiple-Line Graph](https://github.com/nfujikad/PyBer_Analysis/blob/main/Resources/Multiple_Line_Graph.png)

## Summary
1.  As mentioned above, an interesting take would be to expand the data into a 12 month period to see how it fluxuates throughout the year. This will take into consideration holidays, school, tourism, etc. With this information, prices can be adjusted. 

2. Additionally, more research should be done to understand why in urban areas the average driver fare is lower than the average ride fare whereas, in suburban and rural the average driver fare is higher than the average ride fare. There is a discrepancy in whether the rides from rural to urban are considered rural or urban and are recorded as such. 

3. Finally, it would be beneficial to track ride distance and time. Are prices dependent on time or distance, and which is more beneficial for revenue? Are rural and suburban prices higher because the drive is further away or because it takes longer? are urban total rides and total fares higher because the rides are shorter and thus at a higher frequency?
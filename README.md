# Ford GoBike System Analysis
George Helsby

## Dataset
The dataset consists of roughly 1.8 million bike rides from Ford's GoBike bike sharing system from the year 2018. The data was collected solely in San Francisco. 

The variables for each individual ride include the trip start & end time, start & end station, trip duration in seconds as well as extra information such as user type.

## Summary of Findings
The first finding was that **customers ride for much longer on average than subscribers**. Customers are defined as those riders who do not have any monthly or annual membership to the system and instead ride pay-per-minute. What was discovered is that customers ride on average about 3 times longer than subscribers while only making up about 15% of all riders.

Secondly, after discovering that there was very minimal seasonal fluctutation in trip durations in San Francisco I downloaded & imported 2018's dataset for New York City's Citibike system. After comparing the two cities it was clear that there was a **significant difference in seasonal fluctuations of ride length between San Fran and NYC**. This was to be expected as San Francisco has a notoiously temperate climate and New York has hot summers as well as freezing/snowy winters. 

Lastly, I found that there is a significant difference in what time of day & what day of the week riders use the systems. Specifically that **customers almost exclusively ride on the weekends and subscribers are the opposite**, essentially only riding during weekdays. In addition to this a bimodality was observed for the subscriber group around **8am and 5pm, i.e work commute times**. Therefore it is clear that subsribers are largely locals who predominantly use the service for shorter work commutes whereas customers tend to be tourists who use the bike sharing systems for longer 'sightseeing trips'.

# Bike_Rental

**Authors:** Fabio Tavares and Lilian Stein

**Email:** fabio.tavares.fma@gmail.com

**LinkedIn:** [Fabiohsst](https://www.linkedin.com/in/fabiohsst/) and [Liliamcristinestein](https://www.linkedin.com/in/liliamcristinestein/)

## Task
The main goal of this notebook was to calculate hourly flow of bikes per day of the week and visualize the variance of the peak times during the period analysed and define patterns of peaks (if there are any) considering peak times in car's traffic in Dublin city found in TomTom website 2. The just mentioned displays a heatmap with peaks at 8am, during the afternoon with stronger peaks around 2pm, 4pm and 5pm. Thereafter, if successful, reproduce that method in specific stands enabling singular visualizations.

As direction points:

How much of the data collected is really usefull to complete the task.
What's the best way to find the daily flow.
Trace stands as in which displays highest flux.
For that, data was collected starting at Friday the 2nd and finishing at Thursday the 8th, completing 7 days of data 1. On overal, data was collect from 7:45am to 7:30pm with some variation in starting and finishing times and for that reason, in the analysis, the data considered will be from 8am to 7pm.

## Conclusion
Discussing the results of our analysis in regards to our goals, it was possible to obtain a daily flow per hour and track the patterns of peak hours we were looking for taking in account all stations together. We could also track stations with high and low flows and by using their numbers, an individual flow per day could be plotted again in order to gain insights. However, our analysis did not provide distinction of inflows or outflows, therefore it should only be used as a mean the visualize peak times of flow alone during the day.

About our findings, Dublin city displays peaks of flows that are relatable to usual busy times found in the traffic of cars as mentioned in the task brief. Those peak times normally are as its highest flows starting on Mondays throughout the week. When they reach Friday, a reduction starts to appear terminating on low flows and peaks on the weekend. We assume those similarities are due to users that commute to work or that commute to school/universities. Weekend days are usually slower then because many of those weekdays users don't need to commute.

There were also some findings when exploring the content of the variables, e.g. some specific occurrences (26) where stands were disconnected from its terminal and that interruption could be something to be investigated. None of the stations offer bonus to its users and only 5 offer payment options on the terminals. There were no electric bikes with internal batteries found on the data.Finally, as an evaluation, we feel we met our goals and work efforts dispended on this report were equaly, 50% - 50%.

## References
[1]: API docummentation. Available on: https://developer.jcdecaux.com/#/opendata/vls?page=dynamic. (Last access: 09/12/2022)

[2]: Dublin Traffic available on: https://www.tomtom.com/traffic-index/dublin-traffic/. (Access: 15/12/2022)

# Exploring flights dataset(2008)
## by Franz Tseng


## Dataset

> The data contains 2389217 rows of data and 29 features about fight information in the year of 2008. While the 2008.csv dataset is still too large considering the RAM I have, therefore, I removed 14 features, which I won't use for the analysis, and save the new dataset with 15 features as "flight2008.csv" for later use.
The link the original dataset was downloaded: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7


## Summary of Findings

> The proportion of flights diversion and cencellation is much lower than those not diverted or cancelled and the ratio of cancellation is higher than that of diversion.
> Security delay is the least frequent cause of delay.
> Flying distance and time on the flight do not correlated to flight delay in a linear fashion
> The relationship between origin airport and departure delay is not clear. However, when it comes to the proportion of extreme delay(longer than 6 hours), there is clear difference between airports.

## Key Insights for Presentation

> Weather delay is partly related to the location of the airport, however, some carriers have way higher average delay at certain airport in which the average delay among other carriers are much lower. This cannot be fully explained by the fact that certain airport locations tend to have bad weather.
> The two carriers EV and OH have specifically high average weather delay time than other. While OH tend to have weather caused delay in most of the airports, EV has weather delay mostly in Atlanta where it has way more flights than in other airports. That means EV's weather delay is more likely to be due to the location of the airport, but not OH's weather delay.
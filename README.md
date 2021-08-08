#### Gas Tracking

## Overview

I have been recording how much gas I use and how far I drive between fill ups since 2017. When I fill my tank, I record the amount of gas, the total cost of the gas, 
and how many miles driven since the last pitstop. Using this data, I can plot the price per gallon over time. In this repository, I explore how gas has gotten more
expensive and I perform some statistical analysis on my driving habits.

## Notebooks
I have two jupyter notebooks where I do my analysis. In gasbyyear, I perform some basic data manipulation like changing data types, making new columns, and filter data
by year. Then, I visualize the cost of gas between 2018 and 2019 and perform a t-test to see if there is a statistical difference in the cost of gas. There was not.

In the notebook called gasmileage, I compare my driving efficiency in 2019 to 2020. I start with some data processing like removing dollar signs and changing datatypes.
I also make new dataframes for the years in question and make a quick visual of the miles per gallon for both years. Finally, I performed a t-test and found that I
drove more efficiently in 2020 than in 2019 by about five MPG.


## Next Steps

The next phase of this data collection is to use a datalogger. I have found a good option called the Freematics One+. it is an arduino-based OBD-II logger.

The first step is to buy the product and get it working with the basic fuctionality. This includes, speed, gps, rpm, throttle, engine load, fuel pressure, and others.
I will need to verify that these are all working for my vehicle and see what other data is available to be collected. Real-time fuel use would be great.

I think it would be possible to calculate the total drag forces on the car to monitor for spikes. I know that air density will play a role, but I do not know what error that would introduce if esimated. Otherwise, it would require more sensors for pressure and temperature. I can estimate the frontal area of the car and the drag coefficient.

I think I would need to calculate a baseline total drag force and produce a table for drag as a function of speed. Then, use that as reference to calculate how the drag coefficient changes. All, drag coefficient changes would then be measured from the baseline which may not be accurate or ideal. 

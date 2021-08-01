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

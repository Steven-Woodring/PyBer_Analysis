# PyBer Analysis with Matplotlib
### An analysis of hypothetical rideshare data to inform business decisions

## Overview
#### This exploratory analysis takes large sets of data from a hypothetical ride-sharing company, PyBer, and showcases the relationship between the type of city and the number of drivers and riders, as well as the percentage of total fares, riders, and drivers by type of city. The visualizations produced using Matplotlib will help PyBer improve access to ride-sharing services, and determine affordability for under-served neighborhoods.

## Results

### Summary DataFrame
#### Looking at the summary DataFrame, it is obvious that Urban cities require the most resources as there were 1,625 rides provided in these city types over the first 4 months of 2019 compared to just 625 and 125 rides in Suburban and Rural cities, respectively. Despite less demand, it is possible that more drivers are needed to fulfill the needs of Suburban and Rural neighborhoods. Urban cities have 2,405 total drivers (1.48 drivers per ride), while Suburban and Rural cities have only 490 drivers (0.78 drivers per ride) and 78 drivers (0.62 drivers per ride), respectively. Allocating some additional drivers to non-Urban cities may also boost profits as both the average fare per ride and average fare per driver are highest in Rural settings and lowest in Urban cities, with Suburbia falling in the middle. While Urban cities contribute the vast majority of PyBer’s fare revenue (nearly $40K compared to less than $25K in Suburban and Rural cities combined), non-Urban neighborhoods seem to be more profitable and under-utilized.

<img width="596" alt="Screen Shot 2022-01-21 at 4 37 10 PM" src="https://user-images.githubusercontent.com/95303422/150603403-5d851cc8-7515-4663-a10c-c02fd7365245.png">

### Multiple-Line Chart
#### In terms of the weekly breakdown of fares by city type, Suburban fares seem to be more consistent than fares in Urban and Suburban cities. Throughout March, Urban fares regularly varied between $250 and $500 week-by-week. Rural fares experienced similar volatility, with many weeks pulling in $200 or less in total fares. Meanwhile, the line chart for Suburban fares is more gradual, with only one large spike and immediate drop-off at the end of February. Additionally, the total fares in Urban cities seemed to be most affected by the cold-weather months, with the weekly revenues hovering around just $2K in January and failing to exceed $2,250 before late February.

<img width="993" alt="Screen Shot 2022-01-21 at 4 38 15 PM" src="https://user-images.githubusercontent.com/95303422/150603515-77874c82-0ce3-4d67-8cf8-cc2f618d79b0.png">

## Summary

### Business Recommendation #1
#### Based on the results of the analysis mentioned above, I would first suggest to the PyBer CEO that the company establish a larger driver presence in Suburban and Rural neighborhoods. These cities are significantly more profitable than Urban areas as both have an average fare per ride of over $30, compared to only $24.53 in Urban cities.

### Business Recommendation #2
#### Secondly, I would slightly raise prices in Urban cities. With a lot of drivers and high demand for rides in Urban areas, a small price hike would go a long way in boosting PyBer’s overall revenue as well as the average fare per ride and fare per Driver for these cities.

### Business Recommendation #3
#### Lastly, in conjunction with the price increase, I would suggest that the company offer a discount for the winter months that would more than cancel out the price hike. With this new cold weather discount, PyBer may be able to make their revenue Urban fares revenue more consistent, and therefore sure up their cash flows year-round.

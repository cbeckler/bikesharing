# Citi Bike in NYC

## Overview of Project

### Purpose

When the city of Des Moines was considering whether or not to fund a bike-sharing program, the analyst was asked to create a presentation to evaluate a similar program in New York City. Using data from August of 2019 for the Citi Bike program, the analyst created a Tableau report which can be found [here](https://public.tableau.com/views/NYCCitiBikes_16676703070250/NYCCitiBikePresentation?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link). 

### Results

The first page of the report was a general overview of the NYC program, as seen here:

![report page 1](https://github.com/cbeckler/bikesharing/blob/main/Resources/page1.png)

Over 2 million rides were taken in August 2019. It it also clear that trip duration tended to increase as age decreased, and that peak hours tended to be in the evenings. Bike start points also clustered around Manhatten.

![gender pie](https://github.com/cbeckler/bikesharing/blob/main/Resources/gender.png)

Looking more closely at the gender visualization, it is clear most customers were male.

![subscriber pie](https://github.com/cbeckler/bikesharing/blob/main/Resources/customer.png)

The vast majority of customers were also subscribers, which is generally indicative of good long term health of a program, since these customers are likely to come back for additional rides.

![bike utilization graphic](https://github.com/cbeckler/bikesharing/blob/main/Resources/bikes.png)

The interactive bike utilization graphic allows users to see how many seconds in duration each bike has been used for customer travel.

The second page of the report was an analysis of how much time bikes were checked out during their trips:

![report page 2](https://github.com/cbeckler/bikesharing/blob/main/Resources/page2.png)

The vast majority of all trips were an hour or shorter in duration, a trend which persisted across genders.

The third page of the report was an analysis of trips by weekday:

![report page 3](https://github.com/cbeckler/bikesharing/blob/main/Resources/page3.png)

The heavist days for trips were Monday, Tuesday, and Thursday. When further broken down by gender, these trends were seen in the male subscriber data. Our previous analyses showed these make up the majority of the NYC Citi Bike client base.

The fourth page of the report was an analysis of trips by weekday, start time, and gender:

![report page 4](https://github.com/cbeckler/bikesharing/blob/main/Resources/page4.png)

In this visualization, the heaviest usages were morning and evenings by males, generally matching up with standard commute hours. Combined with the previous analysis by gender and customer type, this may indicate the male subscribers are using the Citi Bike service as a regular alternative to car commutes.

## Summary

### Program Viability

The results of this analysis are promising. They suggest that rather than being a one-off novelty, customers are using Citi Bike services as a regular use replacement for commuting. The city of Des Moines may see both positive cash flow from program revenue and a decrease in pollution if program adoption goes well. Areas of weakness seem to be that females are less likely to use the program, so targeting that demographic with special advertising campaigns may be advisable. The analyst would recommend that research be done to find the prime commute spots in Des Moines and pilot a bike sharing program in that area.

### Further Analyses

If the city would prefer further analyses of the NYC data be done before committing to a pilot program, the analyst has two recommendations:

1. An analysis of checkout times in minutes by customer type would allow us to see if there are differences in the duration of rides used by regular subscribers versus non-subscriber clients. This could be plotted in the same manner as the analysis of checkout times by gender, with customer type replacing gender.
2. An analysis of customer type by birth year would allow us to see if regular subscribers are in the demographic age range we would expect from working, non-retired adults. The analyst would recommend a stacked bar chart, with birth year on the X axis and number of clients on the Y, with color fill in the bars to indicate subscriber versus non-subscriber breakdown.

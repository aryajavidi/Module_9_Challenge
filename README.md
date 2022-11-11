# Module_9_Challenge

## Overview of the statistical analysis

The purpose of this analysis was to use Python, Pandas, and SQLAlchemy, to filter the date column of the Measurements table in the hawaii.sqlite database to obtain the temperatures for the month of June and December. We then converted the temperatures into a list and used this list to create a dataframe that would provide summary statistics for the months of june and december. We can use these statistics to identify and report on differences in weather between June and December.


## Results

The average temperature in June, approximately 75 degrees, is four degrees higher than the  average temperature in the month of December, which was approximately 71. The temperatures for June had a much smaller distribution, with majority fitting within one standard deviation from the mean. The standard deviation for June was slightly lower than that of December, meaning that temperatures in June were more normalized and closer to the mean temperature than the slighly more variable temperatures in December. The standard deviation for June was 3.25 degrees, while December's was 3.74. 

## Summary

To summarize, the temperature difference between June and December is very low. When determining whether or not a surf and ice cream shop could be operational year round, we can see that the minimum temperature in december is about 56 degrees, which may be too low for some people to be interested in ice cream and surfing, but would not prevent people from leaving their homes to go out. There will not be a snow day that prevents people from surfing, and for the most part the weather stays relatively warm, making a surf and ice cream shop viable to see business year round. Additional queries that could make this analysis more accurate could include data from other months over the years to determine trends in weather and how it has changed over the years, perhaps showing an upward trend in warm weather as global warming continues to rise temepratures. Another query that could prove to be valuable could be location data, showing the other types of businesses nearby, the average age ranges and demographics of consumers, and the ammount of competition in the area to determine if this shop would be able to find success. 

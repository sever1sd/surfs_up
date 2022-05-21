# Surfs Up Analysis
## Purpose
The purpose of this analysis was to evaluate the relative temperatures in Oahu, Hawaii in order to determine the best locales for a start up  ice cream business that is reliant on good weather. This specific analysis is an additional ad hoc analysis of temperature for the months of June and December in order to determine if the start up will be sustainable year-round.

## Results

There are a few differences between the months of June and December. These differences can be summarized as:

1. December has generally lower temperatures than June, with a mean temp ~4 degrees lower
2. December has slightly more variability in temperature in June, with a standard deviation ~0.489 degrees higher
3. December also has a wider range in temps, with a range spread of ~7.25% as opposed to June's range spread of ~5.48%

**Summary Table**

![alt text](https://github.com/sever1sd/surfs_up/blob/fba0d36fcc57e7fa317261a688ab9c47c0927b18/Both_Summary%20stats.png)

## Summary
Generally, the temperatures between the two months are relatively the same. While December is marginally lower and does seem to have more variability, the differences are only a few degrees at a time. The 25th percentile temperature in December is still around 70 degrees. Due to this relatively minimal change in temperature and temperatures generally being around 70 degrees or greater, the ice cream start up should be viable all year round.

However, to better understand the true climate conditions of Oahu, Hawaii, additional queries on the data should be conducted. Two queries, on one March data and one one October data, should give a clearer picture of the year-round weather for the startup.

Below is a screenshot of the code and results for the two queries:

![alt text](https://github.com/sever1sd/surfs_up/blob/8670dd92dca62a2c3bb604bcd52741590fb8ef32/additional%20queries.png)

While it's clear the temps remain relatively consistent in relation to June and December, it is notable that both months have minimums below 70 and, in the case of March, sometimes drift into the low 50s. This isn't a huge concern as the days are still generally at 70 degrees or above when considering the 25th percentile. This indicates that the business should still be viable year-round, but some precautions should be considered for the few days a year that fall into the low-50s. 

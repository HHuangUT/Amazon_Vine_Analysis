# Amazon_Vine_Analysis
## Overview

Determine if there is any bias toward favorable reviews from Vine members in your dataset (Furniture).

## Results

How many Vine reviews and non-Vine reviews were there?

- Vine Reviews: 2,775 (0.35%)
- Non-Vine Reviews: 789,338 (99.65%)

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- 5-Star Vine Reviews: 1,356 (0.30%)
- 5-Star Non-Vine Reviews: 446,360 (99.70%)

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- 5-Star % of Vine Ratings: 1,356 (0.30%)
- 5-Star % of Non-Vine Ratings: 446,360 (99.70%)

## Summary

1. The majority of views are from Non-Vine (99.65%)
2. 5-Star reviews *almost* come exclusively from Non-Vine (99.70%)
3. There are some 5-Star reviews from Vine, and filtering for "helpful" reviews does improve the 5-Star frequency of the Vine set.


### Reccomendations
1. Looking at purchase dates and surges in orders will help determine times of the year where influxes of certain reviews come in.
2. Since there is a big number difference in Vine v. Non-Vine reviews, one could resize the dataset to only include the products reviewed via Vine- to enable a more direct comparison
3. The Vine does yield higher 5-Star Ratings per review, but I would recommend testing with more specific products that can directly be compared to other reviews.
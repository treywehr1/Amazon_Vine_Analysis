# Amazon Vine Analysis

## Overview of Analysis

The purpose of the below analysis was to acquire data regarding Amazon video game reviews via Google Colab/Apache Spark and PostgreSQL to then extract and run pandas analysis to determine whether or not there was significant differences between vine (paid) and not vine (unpaid) reviews.

## Results

 - Upon running the pandas .value_counts() and or .describe() method(s) it was found that there were 4,291 total "vine" reviews and 1,781,706 "not vine" reviews.
 - Of the total number of "vine" reviews; .value_counts() on the 'star_rating' column revealed that 1,607 were a 5-star rating.
 - Of the total number of "not vine" reviews; .value_counts() on the 'star_rating' column revealed that 1,025,317 were a 5-star rating.
 - For "vine" reviews, using .value_counts(normalize=True), this amounted to 37.5% of reviews being 5-stars.
 - For "not vine" reviews, using .value_counts(normalize=True), this amounted to 57.5% of reviews being 5-stars.
 - Images provided below support the above findings
 
 ![](https://github.com/treywehr1/Amazon_Vine_Analysis/blob/main/resources/total_counts.png)
 ![]()
 ![]()
 ![]()
 
 ## Conclusion

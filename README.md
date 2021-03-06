# Amazon_Vine_Analysis
An analysis of Amazon product reviews from the Amazon Vine program.
## Data Citation
ð® The dataset used in this analysis is the Digital Video Game Reviews dataset. ð "https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Digital_Video_Games_v1_00.tsv.gz"
## Overview
* ðThe purpose of this analysis was to use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then use PySpark to determine if there is any bias toward favorable reviews from Vine members in the Digital Video Game Reviews dataset.
  * âï¸ The Table_check.png shows that the data was succesfully loaded into pgAdmin. ![Table_check.png](https://github.com/RuthLD/Amazon_Vine_Analysis/blob/main/Resources/Table_check.png) 
## Results
* The paid_reviews image shows the total number of paid review in the Digital Video Game Reviews dataset as part of the Amazon Vine Program.
 * ![paid_reviews.png](https://github.com/RuthLD/Amazon_Vine_Analysis/blob/main/Resources/paid_reviews.png) 
* The uppaid_reviews image show the total number of uppaid review in the Digital Video Game Reviews dataset.
 * ![upaid_reviews.png](https://github.com/RuthLD/Amazon_Vine_Analysis/blob/main/Resources/unpaid_reviews.png)
### Total Vine reviews & non-Vine reviews
* Vine reviews = 0
* non-Vine reviews = 1685
### Total 5 star Vine reviews & non-Vine reviews
* â­â­â­â­â­ Vine reviews = 0
* â­â­â­â­â­ non-Vine reviews = 631
### Percentage of 5 star Vine reviews & non-Vine reviews
* Vine reviews = 0
* non-Vine reviews = 37.45%
## Summary
* Based on the results there is no bias in the Digital Video Game Reviews dataset as there were no paided reviews.
* Digital Video Game Reviews may have fewer reviews per product title so combining the data set with the Video Game Reviews dataset (which is the physical edition of the product) may offer different results for the number of review and participates in the Amazon Vine Program.

# Amazon Vine Analysis
## Overview 
Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

In this analysis, we focused onm the US reviews for video games. 

## Results 
### Total 
* Vine reviews - 94
* Non-Vine Reviews - 40471
### 5 Star reviews 
* Vine reviews - 48
* Non-Vine Reviews - 15663

The percentage of reviews in the Vine program that were 5 stars was 51%, while the percentage of reviews that we non-vine were just 39%. This leads us to believe that there is a favorable, positive bias from Vine members in the dataset. If we really wanted to see if there were more consistent bias towards Vine members, we should conduct an analysis of all specific products and compare the percentage of 5 star reviews. Additionally we could also look at the statistical distibution of the rating from 1-5 stars as well, and see if Vine member reviews are favorable. 

# Amazon_Vine_Analysis

### Overview of Analysis of the Vine Program:
The goal of this project is to analyze Amazon's Vine program and determine if there is a bias towards paid and unpaid reviews. Using PySpark and Google Collab, we are able to perform a ETL process to extract the large dataset of video game reviews.

We were able to:
1) Create an AWS RDS instance
2) Load the data into pgAdmin 
3) Perform an analysis using PySpark

#### Resources Used:
- Data Source: [Amazon Review datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
- Video Game Data set: [Video Games Review dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz)

### Results:
* There were 94 paid reviews and 40,471 unpaid reviews
* There were 48 5-star paid reviews and 15,663 5-star unpaid reviews
* 51% of paid reviews were 5 stars, 39% of unpaid reviews were 5 stars. 

![result](https://github.com/DrZubi/Amazon_Vine_Analysis/blob/main/Images/result_summary.PNG)


### Summary:
According to the analysis, there is a positivity bias for reviews in the Vine program. Approximently 51% of paid reviews rated their product 5-star. We can perform another statistical analysis in the genres that the video game falls under (sub-categories) to determine if certian genres are higher rated than others. 


### Additional Images:
Connecting to my AWS database via postgres (PgAdmin):

![example](https://github.com/DrZubi/Amazon_Vine_Analysis/blob/main/Images/postgres.PNG)

Sample table results:

![sample](https://github.com/DrZubi/Amazon_Vine_Analysis/blob/main/Images/sample.PNG)

# JC_Amazon_Vine_Analysis
Module 16: Big Data

# Overview of the analysis:

In this project, a Music dataset was used, by using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin; an analysis was made to determine if there is any bias toward favorable reviews from Vine members in the Music dataset. This summary is to be submitted to the SellBy stakeholders.

2 parts were accomplished:

- D1: Perform ETL on Amazon Product Reviews
- D2: Determine Bias of Vine Reviews

# Resources:
 
  **Data source** [Music Dataset](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Music_v1_00.tsv.gz)

  **Software** Google Colab, PgAdmin, AWS, pySpark.

# Analysis of the Results:

## 1. How many Vine reviews and non-Vine reviews were there?

There were: 7 Vine reviews and 105,979 non-Vine reviews.

![totalreviews_1](/Resources/totalreviews_1.jpg) ![totalreviews_2](/Resources/totalreviews_2.jpg)

## 2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There were: 0 OF 5-stars Vine reviews and 67,580 OF 5-stars non-Vine reviews.

![5stars_1](/Resources/5stars_1.jpg) ![5stars_2](/Resources/5stars_2.jpg)

## 3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- 0.0 % of Vine reviews were 5-stars
- 63.77 % of non-Vine reviews were 5-stars

![percentage](/Resources/percentage.jpg)

# Summary:

The purpose of this analysis is to analyze and determine if there is any bias toward favorable reviews from Vine members in the dataset:

- Positivity bias for reviews in the Vine program

Calculations show that there is significant difference between the reviews of Vine and non-Vine with 5-stars, the results show that percentage of 5 stars Vine reviews is 0.0% while the percentage of 5 stars non-Vine reviews is 63.77%. Non-Vine reviews have way higher percentage of the 5 stars reviews. The Vine reviews had only 3 and 4 stars ratings.

- Additional analyses and suggestions

To improve the analysis the percentage for all stars reviews can be calculated, as shown below:

![percentageallstars_1](/Resources/percentageallstars_1.jpg) ![percentageallstars_2](/Resources/percentageallstars_2.jpg)

People call me JC, the short for [Juanita C. Nunez](https://www.linkedin.com/in/juanitacamargonunez/). Contact me for any questions! I love networking, so here you go  my [LinkedIn] (https://www.linkedin.com/in/juanitacamargonunez/) :)



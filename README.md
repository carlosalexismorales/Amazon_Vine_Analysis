# Amazon_Vine_Analysis

Analysis on Amazon's vine review program using PySpark and AWS RDS with PostgreSQL

## Project Overview

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. This project analyzes Amazon reviews written by members of the paid Amazon Vine program and determines whether there is a bias toward favorable reviews from Vine members.
 
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.

The data set used for this analysis was reviews for video games. 

## Challenge Overview

1. Use PySpark to read in a CSV file
2. Use PySpark methods and functions to get DataFrame information
3. Use PySpark functions to transform and filter data
4. Create a RDS on AWS
5. Connect pgAdmin to a AWS RDS
6. Use PySpark to perform ETL on Amazon Product Reviews
7. Determine Bias of Vine Reviews


## Results

- How many Vine reviews and non-Vine reviews were there?



In the images below, we see that there was 94 Vine reviews and 40,471 non-Vine reviews

<img width="792" alt="Screen Shot 2022-09-14 at 7 59 01 PM" src="https://user-images.githubusercontent.com/102444078/190303464-a4b49bb6-05df-431c-bb7c-9757d8f0ded7.png">




<img width="607" alt="Screen Shot 2022-09-14 at 7 59 29 PM" src="https://user-images.githubusercontent.com/102444078/190303531-2b799f4e-aed8-42cd-95f3-3538dfc82617.png">


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?



- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?









## Summary



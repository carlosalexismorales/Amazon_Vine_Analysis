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



In the images below, we see that there was 94 Vine reviews and 40,471 non-Vine reviews.





<img width="792" alt="Screen Shot 2022-09-14 at 7 59 01 PM" src="https://user-images.githubusercontent.com/102444078/190303464-a4b49bb6-05df-431c-bb7c-9757d8f0ded7.png">








<img width="607" alt="Screen Shot 2022-09-14 at 7 59 29 PM" src="https://user-images.githubusercontent.com/102444078/190303531-2b799f4e-aed8-42cd-95f3-3538dfc82617.png">


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?





In the images below, we see that there were 48 Vine 5 star views and 15,663 non-Vine 5 star reviews. 






<img width="746" alt="Screen Shot 2022-09-14 at 8 03 10 PM" src="https://user-images.githubusercontent.com/102444078/190304016-9e5b7b6f-b62e-4ff0-aa1a-0954632553ec.png">







<img width="742" alt="Screen Shot 2022-09-14 at 8 03 44 PM" src="https://user-images.githubusercontent.com/102444078/190304111-bdc65897-e123-43e3-8b7f-a66acc896f17.png">







- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?



In the images below, we see that that the percentage of Vine reviews that were 5 stars is 51.1% and the percentage of non-Vine reviews that were 5 stars is 38.7%. 




<img width="723" alt="Screen Shot 2022-09-14 at 8 05 25 PM" src="https://user-images.githubusercontent.com/102444078/190304319-bbdaa51b-caa9-4f86-99bb-3493a3ae0050.png">








<img width="758" alt="Screen Shot 2022-09-14 at 8 05 37 PM" src="https://user-images.githubusercontent.com/102444078/190304352-6ea2fe23-6abc-4568-90e9-11ec98ebacca.png">






## Summary




Comparing the percentages of 5 star Vine reviesws to non-Vine 5 reviews, we can determine that there was a positivity bias since 51% > 39%. for reviews in the Vine program.

One additional analysis we could do is compare the rest of the Vine and non-Vine reviews to see if there is a positive bias across the board. That can help us determine if Vine reviews have an overall positive bias regardless of how the products were rated. 


# Amazon_Vine_Analysis
![coverpic](https://user-images.githubusercontent.com/95388367/162640050-ffd08bb3-66d0-42c6-ac53-6ac7d00ddbeb.jpeg)

## Overview
Soon after completion of my Bootcamp Certification, I landed a job at BigMarket. BigMarket helps businesses optimize their marketing efforts. The client was $ellbuy whom is was about to launch a large catalog of produts on a website. Their request was to know how their reviews compare to similar reviews of competitors. They also are interested in enrolling in a program that gives out free products to select customer but they want to find out if it's worth the cost. Due to achieving success with them, I've been tasked with another large project. 

I'm analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

Below are my results from the analysis. Due to having many catagories of datasets form clothing apparel to wireless products, I've shared of the them, BEAUTY. I've used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then use PySpark to determine if there is any bias toward favorable reviews from Vine members in your dataset.




### Results
- The total Vine reviews from the dataset were 647.

<img width="292" alt="total paid" src="https://user-images.githubusercontent.com/95388367/162640252-b21d7470-582b-485a-96be-21cb7e7bc220.png">


- The total non-Vine reviews from the dataset were 74,113.

![total unpaid](https://user-images.githubusercontent.com/95388367/162640217-11bc9f85-4fd1-46e7-a635-76dcaf6e868b.png)


- The total Vine reviews that recieved a 5 star rating were 229.

<img width="1311" alt="paid five star " src="https://user-images.githubusercontent.com/95388367/162640274-e9b9906a-3aee-4285-b915-3e995525d3a7.png">


- The total non-Vine reviews that recieved a 5 star rating were 43,217.

<img width="725" alt="unpaid five star" src="https://user-images.githubusercontent.com/95388367/162640280-8f1b750a-4062-41c7-bb64-d3db5f3238df.png">


- From the reviews, the total Vine reviwes were 35.39% rounded we can say 36%. 

<img width="389" alt="paid percentage " src="https://user-images.githubusercontent.com/95388367/162640287-0c6e9872-5b31-4bd8-b1d2-69fb4c4a096f.png">


- From the reviews, the total non-Vine reviews were 58.31% rounded we can say 58%.

<img width="335" alt="unpaid percentage " src="https://user-images.githubusercontent.com/95388367/162640293-d424c325-f2b6-4dca-b7cd-d8b2f1e6b406.png">


### Summary
From my above results I can say the reviews in the Vine program are not bias. As we can see the majority of reviews 58% are non-Vine reviews. Reviews that have come from the Vine program make up only 36%. To put it more in clear words out of 74,760 reviews, only 647 were from the paid Vine Program. 
An additional analysis that can be done to make my statment more stronger is from this data set compare by each type of beauty product. In this dataset there are many different brands and items of "BEAUTY". Just the being in the word "Beauty" can mean a ton of products. 


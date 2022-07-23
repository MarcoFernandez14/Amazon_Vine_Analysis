# Amazon_Vine_Analysis
#### Environment
Code editor: Colab Notebooks, Pgadmin  
Language: Spark, SQL  
Tools: AWS - S3 RDS  

## Overview
The purpose of this project is to analyze one of *Amazon Review datasets* in order to determine if there is bias towards favorable reviews from Vine members.  
The analysis requires to perform the ETL process to the dataset which was done using Spark in Google Cola Notebooks.  
The dataset I chose is *amazon_reviews_us_Video_Games_v1_00.tsv.gz*  

## Results
The results of the analysis are shown below.    
* Vine Reviews    
![Vine Reviews](https://github.com/MarcoFernandez14/Amazon_Vine_Analysis/blob/main/Resources/paid_number_reviews.png) 
* Non-Vine Reviews   
![Non-Vine Reviews](https://github.com/MarcoFernandez14/Amazon_Vine_Analysis/blob/main/Resources/unpaid_number_reviews.png)  
* Vine Reviews with 5 stars    
![Vine Reviews with 5 stars](https://github.com/MarcoFernandez14/Amazon_Vine_Analysis/blob/main/Resources/paid_number_reviews_fivestars.png)
* Non-Vine Reviews with 5 stars    
![Non-Vine Reviews with 5 stars ](https://github.com/MarcoFernandez14/Amazon_Vine_Analysis/blob/main/Resources/unpaid_number_reviews_fivestars.png)
* Percentage of Vine Reviews with 5 stars    
![Percentage of Vine Reviews with 5 stars](https://github.com/MarcoFernandez14/Amazon_Vine_Analysis/blob/main/Resources/percentage_paid_reviews_fivestars.png)
* Percentage Non-Vine Reviews with 5 stars    
![Percentage Non-Vine Reviews with 5 stars ](https://github.com/MarcoFernandez14/Amazon_Vine_Analysis/blob/main/Resources/percentage_unpaid_reviews_fivestars.png)

## Summary
The filtered dataframe results show that the five-star reviews are 51% of the total in the Vine program and 39% of the total in non-Vine. This could indicate a positive bias. However, the analysis should be extended to confirm this hypothesis. We could also analyze the trends in 1 star reviews or we could check the results without filtering the rows where *helpful votes* are majority.


 

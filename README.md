# Big Data
![image](https://user-images.githubusercontent.com/112978144/224561454-1b1e12dc-5efa-4308-b934-b1016f9c3fe9.png)

This module is about Big Data that refers to extremely large and complex data sets that cannot be effectively analyzed using traditional data processing methods. These data sets can be generated from a variety of sources such as social media, financial transactions, scientific research, sensor data, and many others.

The characteristics of big data are the volume, velocity, and variety of the data. Volume refers to the large size of the data. Velocity refers to the speed at which data is generated and must be processed. Variety refers to the different types and formats of data.

Big data technologies and tools are used to store, manage, and analyze these large data sets. These technologies include distributed storage systems like Hadoop, NoSQL databases, and data processing frameworks like Spark. Big data analytics techniques like machine learning, data mining, and natural language processing are used to extract insights and patterns from the data to support decision-making, research, and business strategies.
In this challenge Amazon vine analysis is perfored using Big Data technologies

# Amazon_Vine_Analysis

![image](https://user-images.githubusercontent.com/112978144/224560386-058646f7-8afc-4192-89df-16e9b74c7253.png)

# OverView
*- Purpose
The purpose of this analysis is to perform the ETL process using Pyspark to extract one of the datasets from Amazon reviews from the members of the paid Amazon Vine program. In order to work on this challenge data is transformed , connected to an AWS RDS instance, loaded the transformed data into pgAdmin, and then used PySpark to determine if there were any biases towards favorable reviews from Vine members in the dataset.

# Resources

*-Google Colaboratory 
*-PySpark
*-Amazon Web Services (AWS)
*-PostgreSQL 
*-pgAdmin 4
#-Data source:

*-Amazon Review datasets
*-Amazon Toys Reviews
# Results
We were assigned to address following questions and we extracct the following output
How many Vine reviews and non-Vine reviews were there?
# Vine reviews
We got following vine reviews
There are 1266 vine reviews
![image](https://user-images.githubusercontent.com/112978144/224563137-ba39ea01-4b2b-4d98-ba58-fca88cf98c28.png)
# Non Vine reviews
Non vine reviews are 62028
![image](https://user-images.githubusercontent.com/112978144/224563193-c9229b4b-1ac6-484f-b4ac-e6f159473b32.png)


How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
# Five_Star vine reviews
Five star reviews are 432
![image](https://user-images.githubusercontent.com/112978144/224563306-be64ad36-fb03-4a9d-b603-46dfbf7860ef.png)
# Five star non vine reviews
Five star non vine reviews are 29982
![image](https://user-images.githubusercontent.com/112978144/224563393-fd1b0d37-2039-487d-a2da-96d5d00228eb.png)


What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
# Percentage of 5 star vine reviews
![image](https://user-images.githubusercontent.com/112978144/224563481-fdf4a588-8f3b-4f07-bd14-a66e6076dccd.png)
# Percentage of 5 star Non vine reviews
![image](https://user-images.githubusercontent.com/112978144/224563515-335fa41b-2104-45f3-88fa-3be5f0e90221.png)
# -Summary
While Vine reviews are helpful in providing feedback from verified purchasers who received the product for free, they should be considered alongside other reviews from customers who purchased the product on their own. It's important to read a variety of reviews before making a purchase decision.
In this challenge we find that there is not strong bias toward five-star reviews from paid Amazon Vine reviewers. Vine reviews might show a tendency towards being more critical in their reviews. This conclusion could be further examined by looking at the all star-levels across paid and unpaid reviews. Also, for a more deep analysis, this same meta-analysis should be conducted across a different product catagories and with the same products from different companies.


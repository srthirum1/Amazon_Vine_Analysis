# Amazon_Vine_Analysis
#note: I was not able to push the csv file as it was too large and I am having lots of trouble pushing it forth, though my code should work fine

#1. Overview of the analysis: Explain the purpose of this analysis.
I am analyzing amazon reviews by members, I used an amazon datset, used pyspark to perform ETL process and then oaded that data into pgadmin database. 

#2. Results: Using bulleted lists and images of DataFrames as support, address the following questions:


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
15 were 5 star vine reviews and 4332 was non vine reviews that were 5 stars 

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

32% were 5 star vine reviews and 52% was non vine reviews that were 5 stars 

#3.Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

- I used Pandas to determine if there is any bias toward favorable reviews from Vine members in the dataset and it seems amazon has favorability to 5 star reviews
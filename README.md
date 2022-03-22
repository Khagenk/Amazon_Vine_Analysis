# Amazon_Vine_Analysis
The task of this Chellenge module was to analyze Amazon Reviews written by member of the paid Vine program. Amazon Vine is a program that enables a select group of Amazon customers to post opinions about new and pre-release items to help their fellow customers to make informed purchase decisions.

Data from Amazon’s video games department for US based reviewers was analyzed to determine if having a paid vine review makes difference in the percentage of 5- star reviews. 

In this Challenge the Extract, Transform and Load (ETL) process was used to create a dataset. In addition, Amazon AWS RDS (S3 buckets)  was also used to to create the Video game dataset. From there pgAdmin was utilized to connect with AWS, and creat different DataFrames to match schemas

# Resources
- Google Colab
	- pySpark
- AWS
	- RDS
	- S3
- Jupyter Notebook
	- Python
	- pandas
- pgAdmin

Data 
- Amazon Video Game dataset

# Results

The Vine table contained 1,785,997 rows of data out of those,
the table was transformed to to show only reviews where there
was 20 or more reviews for the Video Game. Doing this reduced 
the dataset to 65,379 rows of reviews.

![Screen Shot 2022-03-22 at 2 55 21 AM](https://user-images.githubusercontent.com/94031446/159430241-3d890f5c-12b9-4f57-b490-965d55dc56bf.png)

![Screen Shot 2022-03-22 at 2 55 31 AM](https://user-images.githubusercontent.com/94031446/159430299-5c54fea4-ba7b-40d9-bddd-a5f6e11eb041.png)

The dataset were further reduced to only include reviews that  
received 50% or more helpful_votes. 

![Screen Shot 2022-03-22 at 3 35 09 AM](https://user-images.githubusercontent.com/94031446/159430585-7fa2a196-3a19-4178-96ec-ec7e06c750ed.png)

Of the paid Vine reviews, only 94 were 5-stars reviews. 

![Screen Shot 2022-03-22 at 3 35 34 AM](https://user-images.githubusercontent.com/94031446/159430614-cc962424-e6e4-485d-a827-5aa2fc623737.png)

of the unpaid reviews, 40471 were 5-star reviews.
![Screen Shot 2022-03-22 at 3 35 45 AM](https://user-images.githubusercontent.com/94031446/159430643-70f346fe-2ddd-4b33-9776-28bbfafdf53f.png)

paid Vine 5-star reviews  accounted for 51.06% of the data, 
vs unpaid  5-star review accounted for 38.70% of the data


![Screen Shot 2022-03-22 at 3 36 00 AM](https://user-images.githubusercontent.com/94031446/159430685-bf6884a6-76bc-47b0-a95b-ab7f45d37b97.png)


# Summary
Based of the analysis of the Amazon Video Game reviews,
Vine reviews did not affect 5- star reviews. Given the analysis, 
although, Vine reviews had more 5-Star reviews, sheer amount of 
number of unpaid 5-star reviews is undeniable. Further analysis is required.
Also, next analysis for category/genera of video games would be an intreating 
analysis to run to provided more useful data for video game maker on their next 
project.


	

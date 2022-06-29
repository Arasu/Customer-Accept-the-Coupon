# Customer-Accept-the-Coupon

Author : Arasu date : 6/28/2022

Introduction
         This data was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. I will apply this data set to train a supervised machine learning model to predict in what situation the drive will accept the coupon.
 we don’t have a lot of missing values except of few columns. Car attribute has more than 99% of missing values so we will simply drop it (probably because this must have been an optional question in the survey) as imputing at so many places could risk changing the distribution of data. Other attributes have around 1% missing values only so we’ll drop those records. 

We can clearly see from the analysis and generated plots that there is a general trend that people who are frequent goers of a venue will accept their discount coupons.

Data Preparation: 

1.	NaN’s handled 
2.	Duplicates are removed 
3.	Dropped few columns which had more NaN’s 
4.	Removed nearly 1% of the records from few columns due to NaN’s 


Here are the findings: 

•	Almost 56.7% coupons are accepted by drivers irrespective of categories. 
•	For the people who drive the same direction accepts the most coupons than the opposite drivers. 
•	Bar coupons widely accepted by customers who goes to bar between 1-8 times in a month and who drives alone. 
•	Carry away coupons are another top acceptable coupon; it is quick grab so mostly drivers accept these coupons
•	For cheap restaurants we can see there are very few people who never visited one and almost everyone accepts the cheap restaurant coupons more often than not
•	For coffee-houses, expensive restaurants and bars people who have visited Almost 1 time or never visited have rejected their respective coupons. Acceptance increases as people’s monthly frequency of going to these venues increases.

Tools used: Python, NumPy, Pandas, Matplotlib, Seaborn


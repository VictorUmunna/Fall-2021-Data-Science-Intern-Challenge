# Fall-2021-Data-Science-Intern-Challenge

Question 1: Given some sample data, write a program to answer the following: click here to access the required data set

On Shopify, we have exactly 100 sneaker shops, and each of these shops sells only one model of shoe. We want to do some analysis of the average order value (AOV). When we look at orders data over a 30 day window, we naively calculate an AOV of $3145.13. Given that we know these shops are selling sneakers, a relatively affordable item, something seems wrong with our analysis. 

A. Think about what could be going wrong with our calculation. Think about a better way to evaluate this data. 
The mean is not the right metrics because the standard deviation is high and there are outliers. Mean is the only measure of central tendency that is always affected by an outlier, so the presence of them makes the mean the wrong metric for the AOV.

B. What metric would you report for this dataset?
Without eliminating the outliers from our dataframe, we will use a metric which is not affected by outliers, which is the Median. This metric is best suited for this siuation.

C. What is its value?
The median value is $284. This is a more reasonable price for the AOV.


Question 2: For this question you’ll need to use SQL. Follow this link to access the data set required for the challenge. Please use queries to answer the following questions. Paste your queries along with your final numerical answers below.

A. How many orders were shipped by Speedy Express in total?
The total number of orders shipped by Speedy Express is 54

B. What is the last name of the employee with the most orders?
The Last name of the employee with the most orders (40) is Peacock

C. What product was ordered the most by customers in Germany?
Boston Crab Meat has the most orders(160 orders) from Germany

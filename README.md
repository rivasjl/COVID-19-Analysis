# COVID-19 Exploratory Analysis
![image](https://user-images.githubusercontent.com/106350577/170891157-5b8870c9-bbfb-4704-b6bd-be250dca5cab.png)

## Goals
The goal of this project is to answer questions that can be made from looking at the datset through the use of data manipulation in SQL and then visualizing our queries using R.
The datsets that are used in this project contain information such as vaccination count, death count, location, time, icu patients, etc...

Skills that were used in this project: Aggregate functions, CTE, Join and Group By, ggplot2

[Code for all plots](https://github.com/rivasjl/COVID-19-Analysis/blob/main/R%20Code%20for%20ggplots)

[Code for queries](https://github.com/rivasjl/COVID-19-Analysis/blob/main/Code%20for%20SQL)

Some questions that can be answered by looking at this dataset are:

 - Which countries have the highest amount of deaths?
 - Which countries have the highest death rate/vaccination rate?
 - How has vaccination rates changed over time?
 
 ## Exploratory Analysis
**1. Which counties have the highest amount of deaths of COVID-19?**


Looking at our query results, we can see that the top 3 countries with the highest amount of deaths are the United States, Brazil, and Mexico. The bar chart shows us that the United States and Brazil have a much higher death count than other countries. The United States has at least 3 times as many deaths as other countries while Brazil has at least 2 times as many deaths. You may look over the death count because of the fact that the United States has a very large population when compared to other countries, but if you look at India which has a population of over 1 billion people. India has a much lower death count than the United States which shows that as a country, India is handling the pandemic much better than the U.S.
 
 SQL Query Results:
 
 ![image](https://user-images.githubusercontent.com/106350577/170848383-8d46f7d2-6b6a-48a6-a8f3-f45ac585f47d.png)
 
 ![top10dc](https://user-images.githubusercontent.com/106350577/170894127-0eff9160-d7d6-4c72-9f14-4ac1a581293f.jpeg)


**2. Which countries have the highest death rate of COVID-19?**

Looking at our query results, we can see that the countries that have the highest death rate of COVID-19 include Vanuatu, Yemen, Mexico, Sudan and Syria. 
One thing that can be noted is that 3 of these countries are found in the middle east. This brings up a question of why these countries have high death rates. Perhaps it is from the people living there not having access to good quality healthcare. Another thing to look at is Vanuatu's death rate which sits at 25%, this is a very high number and is more than at least twice the death rate of countries outside the top 2, but the sample size is very small. We only have a sample size of 4 which means that the true death rate could be lower. Once the sample size increases, there will be a clearer picture as to what the death rate really is.

SQL Query Results:

![image](https://user-images.githubusercontent.com/106350577/170890982-081fca59-c864-4387-b917-ffff95fcfb0a.png)

![deathrateplot](https://user-images.githubusercontent.com/106350577/170894078-38f72387-b1f1-4393-95ab-872f185f621e.jpeg)


**3. Which countries have the highest vaccination rates?**

The countries that have the highest vaccination rates as seen in the query below are Gibraltar, Seychelles, Israel, Cayman Island, Chile. Gibraltar is doing a very good with vaccines, they have a vaccination rate of 95% which is really good. Looking at these countries, these aren't countries that you would expect to be at the top in vaccination rate. You would expect countries that have a high population with good healthcare to be first which is pretty interesting. 

SQL Query Results:

![image](https://user-images.githubusercontent.com/106350577/170892205-2b18099f-075b-4c42-a998-e7a24b4577cc.png)

R Plot

![vaccrateplot](https://user-images.githubusercontent.com/106350577/170894076-8393ed3c-570e-4992-a7bc-cb15e1891eec.jpeg)

**4. How have vaccination rates changed over time in the United States?**

As can be seen in the plot, the vaccination rate has been increasing steadily over time and sits at around 60% currently as of April 2021. If the trend follows this means that in the future we could potentially see a vaccination rate that is over 90%.

SQL Query Results

![image](https://user-images.githubusercontent.com/106350577/170892592-be6c75a0-de5f-4e0a-9d7c-4a50542c42b6.png)

R Plot

![vacrateus](https://user-images.githubusercontent.com/106350577/170893497-f7ff9011-36e0-4ce1-b3eb-034e11191cf5.jpeg)



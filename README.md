# COVID-19 Exploratory and Statistical Analysis
![image](https://user-images.githubusercontent.com/106350577/170891157-5b8870c9-bbfb-4704-b6bd-be250dca5cab.png)

## Goals
The goal of this project is to answer questions that can be made from looking at the datset through the use of data manipulation in SQL and then visualizing our queries using R and creating a dashboard in Tableau.
The datsets that are used in this project contain information such as vaccination count, death count, location, time, icu patients, etc...

Skills that were used in this project: Aggregate functions, CTE, Join and Group By, ggplot2, Hypothesis Testing, Regression Analysis

[Code for all plots](https://github.com/rivasjl/COVID-19-Analysis/blob/main/R%20Code%20for%20ggplots)

Some questions that can be answered by looking at this dataset are:

 - Which countries have the highest amount of deaths?
 - Which countries have the highest death rate/vaccination rate?
 - How has vaccination rates changed over time?
 
 ## Exploratory Analysis
**1. Which counties have the highest amount of deaths of COVID-19?**

 Looking at our query results, we can see that the top 3 countries with the highest amount of deaths are the United States, Brazil, and Mexico
 
 SQL Query Results:
 
 ![image](https://user-images.githubusercontent.com/106350577/170848383-8d46f7d2-6b6a-48a6-a8f3-f45ac585f47d.png)
 

We can use a horizontal bar chart in order to create a visualization for this question and as you can see, the United States has a very high amount of deaths compared to other countries. Excluding Brazil, the United States has at least 3 times as many deaths as the other countries in the chart.

 ![top10dc](https://user-images.githubusercontent.com/106350577/170894127-0eff9160-d7d6-4c72-9f14-4ac1a581293f.jpeg)


**2. Which countries have the highest death rate of COVID-19?**

SQL Query Results:

![image](https://user-images.githubusercontent.com/106350577/170890982-081fca59-c864-4387-b917-ffff95fcfb0a.png)

![deathrateplot](https://user-images.githubusercontent.com/106350577/170894078-38f72387-b1f1-4393-95ab-872f185f621e.jpeg)


**3. Which countries have the highest vaccination rates?**

![image](https://user-images.githubusercontent.com/106350577/170892205-2b18099f-075b-4c42-a998-e7a24b4577cc.png)

![vaccrateplot](https://user-images.githubusercontent.com/106350577/170894076-8393ed3c-570e-4992-a7bc-cb15e1891eec.jpeg)

**4. How have vaccination rates changed over time in the United States?**

![image](https://user-images.githubusercontent.com/106350577/170892592-be6c75a0-de5f-4e0a-9d7c-4a50542c42b6.png)

![vacrateus](https://user-images.githubusercontent.com/106350577/170893497-f7ff9011-36e0-4ce1-b3eb-034e11191cf5.jpeg)

**5. Which continent has the highest percentage of deaths?**

## Statistical Analysis

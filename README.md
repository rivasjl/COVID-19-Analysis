# COVID-19 Exploratory and Statistical Analysis
![image](https://user-images.githubusercontent.com/106350577/170891157-5b8870c9-bbfb-4704-b6bd-be250dca5cab.png)

## Goals
The goal of this project is to answer questions that can be made from looking at the datset through the use of data manipulation in SQL and then visualizing our queries using R and creating a dasboard in Tableau.
The datsets that are used in this project contain information such as vaccination count, death count, location, time, icu patients, etc...
Skills that were used in this project: Aggregate functions, CTE, Join and Group By, ggplot2

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

 ![top10dc](https://user-images.githubusercontent.com/106350577/170890864-0598aae1-d6af-4467-a3c6-90262d1f7f83.jpeg)


**2. Which countries have the highest death rate of COVID-19?**

SQL Query Results:

![image](https://user-images.githubusercontent.com/106350577/170890982-081fca59-c864-4387-b917-ffff95fcfb0a.png)


![deathratetop55](https://user-images.githubusercontent.com/106350577/170890235-aabd2d7a-c60a-42f7-ae7b-93dfebadcc7f.jpeg)

**3. Which countries have the highest vaccination rates?**


**4. How have vaccination rates changed over time?**

## Statistical Analysis

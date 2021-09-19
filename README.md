# Marketing Analitics 
## What I'm happiest with this dataset is tha. I have for the first time have gone beyond my limits. I have done the general data exploration and RFM in a couple of hours. <b /> 
**We are given the dataset composed by 300.000 observations and need to find out the Recency Fequency and Monetary analysis for this dataset**<b /> <b /> 

![image](https://user-images.githubusercontent.com/90762709/133905592-c0d3cb4b-0fd8-4dce-986c-5f24bac4de99.png) <b />

Before starting with the RMF analysis we are going to explore data and find out the answer to the question of how many unique customers are among 300k observations? <b />
> Number of unique customers: 167230 <b />

We are also interested to know what is the distribution of total observations in different countries. <b /> <b /> 
![image](https://user-images.githubusercontent.com/90762709/133923943-318e5975-d130-4f90-bd0e-cf8bd6fd5663.png) <b />

Here we see that the most of the observations are registered in Italy and followed by other EU countries. <b />


We have also another variable which classifies the observation types conversion_name: I'm interested in seeing what are the distribution of those?  <b />  <b /> 
![image](https://user-images.githubusercontent.com/90762709/133924500-eaeced7f-23ea-435b-af9d-dbf760791b11.png) <b />

This visualization however, is the integration with the Tableau. (The link to the dedicated Tableau dashboard is on the [link](https://public.tableau.com/app/profile/ibrahim7264/viz/Marketing_16311865946370/Dashboard1) <br /> <b /> 
![image](https://user-images.githubusercontent.com/90762709/133924515-4ce3f358-7a28-4022-9126-cda628266fad.png) <br />

## Recency Frequency and Monetary:<br />
I have calculated the recency (The first conversion of the lead since the launch of the campaign), frequency (The intensity of the engagements) and monetary (Conversion value for the each customer) on R and below we got the next resulst. <br />
![image](https://user-images.githubusercontent.com/90762709/133924939-e1448bd5-0b9f-447c-bc2d-aadc648c497b.png)<br />
Output: 
  - Average Recency is: 345 days
  - In average every customer makes 2 conversions
  - Conversion value of each customer is around 1k Euro.

## Further analysis can be done?
To understand how the next steps could be done we can plot a correlation matrix as following: <br /><br />
![image](https://user-images.githubusercontent.com/90762709/133925161-27640b03-b1e2-45f0-8b5b-e6becf940c1e.png) <br />
1. There is positive correlation between the days since when they are customers and conversion value margin!
2. Coefficient is 0.06 means for each day more we have 0.06 increase in customer conversion value margin

**Code on R is available do download on the repository**







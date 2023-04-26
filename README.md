# Google-Data-Analytics-Capstone
This is a project from Google Data Analytics professional certificate. A case study was presented and it was required of partakers to clean the data and then answer some questions based on the business task. The analysis process recommended by Google was employed here--- Ask, Prepare, Process, Analyze, Share and Act.

# Scenario
You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore, your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights, your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives must approve your recommendations, so they must be backed up with compelling data insights and professional data visualizations.

# About the company
Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to broad consumer segments. One approach that helped make these things possible was the flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships. Customers who purchase single-ride or full-day passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members. Cyclistic’s finance analysts have concluded that annual members are much more profitable than casual riders. Although the pricing flexibility helps Cyclistic attract more customers, Moreno believes that maximizing the number of annual members will be key to future growth. Rather than creating a marketing campaign that targets all-new customers, Moreno believes there is a very good chance to convert casual riders into members. She notes that casual riders are already aware of the Cyclistic
program and have chosen Cyclistic for their mobility needs. Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into annual members. In order to do that, however, the marketing analyst team needs to better understand how annual members and casual riders differ, why casual riders would buy a membership, and how digital media could affect their marketing tactics. Moreno and her team are interested in analyzing the Cyclistic historical bike trip data to identify trends.


# Ask
This part seeks to determine what the business task wants to answer. 
- How do annual members and casual riders use Cyclistic bikes differently?
- Why would casual riders buy Cyclistic annual memberships?
- How can Cyclistic use digital media to influence casual riders to become members?

# Prepare
The cyclist trip data for January 2022 to December 2022 was used here. It can be found at [Site for data]((https://divvy-tripdata.s3.amazonaws.com/index.html) The data was then renamed to have the year together with the months (for instance 2022_01 which meant the 2022 data for January) and kept in a folder to make the data organized as much as possible.


# Process
The R software was used in the data cleaning process. The following packages were installed and loaded to aid us in the data processing --tidyverse, janitor and lubridate.
Subsequently, we would need to import the csv’s into Rstudio, in which we would use read_csv. Since the data was for individual months, it was necessary to combine the data into one dataset (named combined_df done using bind_row() functions).

The data was then cleaned to remove empty columns in our dataframe and then new columns added as required by the business task.

# Analyze 
The analysis of the work was done using Tableau and it can be viewed here [Tableau Analysis](https://public.tableau.com/app/profile/frank.amo.agyei.owusu/viz/BikeProject-GoogleDataAnalyticsCapstoneCaseStudy1/Dashboard1)




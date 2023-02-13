# Google-Capstone-Project

Table of contents
1) Scenerios 
2) Data Collecting & Data Cleaning
3) Excel
4) Python 
5) Data Visualizations

# 1) Scenerios 
Google has already provided the detailed scernerios and waht i have to do as junior data anlayst here is the brief summary of scenerios 

"You are a junior data analyst working in the marketing analyst team at Cyclistic, a bike-share company in Chicago. The director
of marketing believes the company’s future success depends on maximizing the number of annual memberships. Therefore,
your team wants to understand how casual riders and annual members use Cyclistic bikes differently. From these insights,
your team will design a new marketing strategy to convert casual riders into annual members. But first, Cyclistic executives
must approve your recommendations, so they must be backed up with compelling data insights and professional data
visualizations."

2) Data Collecting 

According to the scenario and situations the question that keeps coming for the report of the project are 
1. How do annual members and casual riders use Cyclistic bikes differently? 
2. Why would casual riders buy Cyclistic annual memberships? 
3. How can Cyclistic use digital media to influence casual riders to become members
These three question are the question which needed the most attention and we have to find answer to solve the 
business decision. 

Data Resources

So for that we have been already provided the data resources which is to be used for the project.
We are using previous 12 months data for analyzation and for the business decision.
The data set was located in this site - Index of bucket "divvy-tripdata"
In that we have used the the data of January 2022 to December 2022 data to answer the question 

(Note: The datasets have a different name because Cyclistic is a fictional company. For the purposes of this case study, the datasets are 
appropriate and will enable you to answer the business questions. The data has been made available by Motivate International Inc. 
under this license.)

3) Excel 

We are using excel for the data cleaning. Which is good tool for the cleaning and formatting of the data 
Cleaning , Formatting and Filtering

1) We have created the two new column named ride_length and day_of week
Ride_length : It was created for knowing how much the rider has ridded the bike
This is formatted to hh:mm:ss for just knowing the time 
By applying formula =(D2-C2)
Day_of_week : this column was created to know the day of week. On which day the rider has 
rided the bike most. It contains the numeric values starting from 1 to 7 in that 1 equals Sunday 
and 7 equals Saturday 
By applying formula =WEEKDAY(C2,1))

![image](https://user-images.githubusercontent.com/91587336/218543587-97fd3518-7938-4415-9c83-1cd4a2d5433c.png)

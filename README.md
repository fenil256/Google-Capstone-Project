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

# 2) Data Collecting 

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

# 3) Excel 

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

2)Changed the format of ride_length to hh:mm:ss for easier calculation 

3) I have removed the row which were containing the value 00:00:00 and more than 23:00:00 in ride 
length Which helped us to reduce some waste data. 
Reason for removing the data : The data which may be entered the by mistake or was some error in the 
system which created this data. We only need the data for the ride which is done on the same day note 
more than that
![image](https://user-images.githubusercontent.com/91587336/218543835-08cf7cd4-45b4-4ab4-9b96-b868e62a7161.png)
![image](https://user-images.githubusercontent.com/91587336/218543882-07e27df0-ab15-43de-91ac-644488978c51.png)

Calculation 
CALCULATED MINIMUM MAXIMUM SUM AND AVERAGE OF THE TOTAL RIDES 
sum of ride	
21857:57:00	
	
average ride length
0:12:47	
maximum ride length
23:00:00	
minimum ride length 
0:01:00	

PIVOT TABLE

CREATED VARIOUS PIVOT TABLE AND CALCULATED MANY QUESTIONS WITH EACH FIELD 
1)	THIS PIVOT TABLE SHOWS THE TOTAL NUMBER OF MEMBER AND CASUAL USERS OF THE JANUARY DATASET

![image](https://user-images.githubusercontent.com/91587336/218544217-2c82dbbf-109a-4d67-be1f-38dec1ddb5b6.png)


2)	The pivot table with total number of rides each day of week 

![image](https://user-images.githubusercontent.com/91587336/218544282-a1b9a9f1-5e4b-4a05-94f2-393b50e4b774.png)


3)	This pivot tbale consist of daysof week tyoes of ride and total number of ride length by each one 
 ![image](https://user-images.githubusercontent.com/91587336/218544318-9dc9102f-1c76-4811-8ee8-abd416e6baf4.png)
        
4)	This pivot tbale shows the busiest time and ride length on that time period
![image](https://user-images.githubusercontent.com/91587336/218544380-4610f9f3-ed4f-488e-91ff-f9c957ed621e.png)

This all the pivot table are created for the future analyses and for the summary of the data which will help us to find the final conclusion on the data and the scenarios given.
 
Charts 
1)	This chart  consist of days of week types of ride and total number of ride length by each o

![image](https://user-images.githubusercontent.com/91587336/218544497-223685e3-10ca-4cc5-a90d-e7baf6b640c7.png)

2	) This chart consist of total number of rides each day of week
![image](https://user-images.githubusercontent.com/91587336/218544547-f2b8fe09-9cfe-4211-96db-22a0a4b90211.png)


3 )  THIS CHART SHOWS THE TOTAL NUMBER OF MEMBER AND CASUAL USERS OF THE JANUARY DATASET

![image](https://user-images.githubusercontent.com/91587336/218544594-a971ceeb-3280-496c-9675-7232077540e0.png)


THIS WHOLE PROCESS OF EXCEL IS REPEATED FOR ALL THE DATASET FROM FEBRUARY TO DECEMBER FOR THE FURTHER ANALYSES 

Merging the data 
After all the sorting and filtering we have merged all the data set into one which consists of row more than 6 million roughly around (6426040) and 8 different column field. 

# 4) Python
Python program for  rechecking the the data set and confirming the values that everything is correct before visualizing 
There’s an separate python file for the codes and that checked  various things for  analyzation 

# 5) Visualization

heres the link of the project visualization 
https://app.powerbi.com/groups/me/reports/edc58d0f-5f33-4f65-816a-ee27dc9b0388/ReportSection50a99f504ba575aadb62


We have used the Power bi for the visualization.
![image](https://user-images.githubusercontent.com/91587336/218545243-52af87b2-ede8-4c58-bbea-b2a229d2663b.png)

As you can see above is the visual  I  have created for the year 2022 trip data for the cyclistic company and we can see the clear visual about the data.

You can see that total hours of ride which was done in whole year.

![image](https://user-images.githubusercontent.com/91587336/218545292-e446fd2c-fcaa-44ec-9da3-9257cea4ca86.png)

I have also added average of the total ride in the visualization 

![image](https://user-images.githubusercontent.com/91587336/218545529-cfeb5310-540d-480d-9b04-a2fa29273ac1.png)

We can see that  total number of member and casual people for the company. We can see that there are 40.93% of casual riders. Which is note the small number which to be ignored, it can bea huge beneficial  for the company  to convert them into a members and make them permanent customers 

![image](https://user-images.githubusercontent.com/91587336/218545597-022c5ab3-0b71-46ba-8839-1c07f3a24de4.png)

As you can see in the data there three major types of ride or bikes are available by the company and there over all use by the users. Its an over all use of the bikes by the users through out the users which we can see that electric and classic bikes are more in demand then docked bike the company can increase there supply for more profit and use the marketing campaign for the bikes to be used.

![image](https://user-images.githubusercontent.com/91587336/218545654-9570519d-3eec-41a1-91e8-92e3b9a50682.png)


Now we look at the use of bike in all over week. Here you can assume that 1 = Sunday and 7 = Saturday so that you don’t confuse by the numbers here we can see that over all performance through out the week was almost equal we can’t see the busiest day for the use of bikes but the maximum use of the bike was on  Saturday with busiest day in the week.

![image](https://user-images.githubusercontent.com/91587336/218545693-a97515a3-8363-4642-a6dd-fd358deb8241.png)


These are the most end station in the chicago here the data set is focusing on the particual tarea or sate in the nation as we can see in the map visualization the most comman endstation was near the michigan lake area which can be said that the users uses bikes more for ride to the lake helps us to know that it can be profitable for doing the business near lake area for there convinence and profit in the business. 

![image](https://user-images.githubusercontent.com/91587336/218545769-0ece4a99-6f03-4fc1-ba7f-a8d29c1c1c1b.png)

We can see here the most number of ride or ride length is done on  July month and with very least rides we can see that January is the month with very least number of ride length . we can here say that users prefer more bikes on the summer season then on 

![image](https://user-images.githubusercontent.com/91587336/218545889-012a7090-8df3-4e16-90a6-f6fb9f293888.png)

winter season we have to make the plans or more good sustainable plans so that more casual users can be converted to members . here we can use this opportunity to make the business  more profitable  by giving discounts  or  more benefits to the members  so that casual member  by the benefits they will buy the subscription plan which is the main goal of the company.

Here the data is representing the schedule throughout the entire day how much the users are using the bikes and how much. On yearly bases we can see that 5 : pm timing is very much busiest and from 5:00 Am it is starting to get busier. Here the company needs to under stand that the supply for bikes on busiest hour shoulf not create any havoc and smoothly the users can use the bikes easily.

Conclusion and Solutions :

Conclusion : Company needs to focus on the winter season on that time the casual users are very low so to increase the members users we need to plan more genuine pricing system on that particular season cause the member are also using less bikes on the winter season.  

Solutions 
By seeing the visualization  above I can  give the answers based on the data result 

1)	  Based on the season we can plan or make different subscription according to the season that can be helpful fo the members and the users we can see that the total riders and ride length both are very low on the winter season we can plan a  budget friendly plan that can casual people can buy and use that plan or offers on the winter season 

2)	 There are many end station near the Michigan lake  we can provide other external services or marketing campaign other then the lake so that more and more people know about the company  and there plans and offers .we can also collab with the  local shops  or the market people which gives us the more customer.


3)	There are more users with electric and casual bike type then the docked bike so we can focus more on electric and classic bike and make it more available to the users so that due to the busiest season or the busiest hour we can supply our product to the users without any supply chain problem to the users.


4)	They can plan more membership or offers with plan by making collab with the local store on the winter season and the spring season

On the basis of the conclusion the stake holders and the team leader  can see the report and apply the solutions  based on the data.
Data needed 

I needed the data on pricing of the membership so that more insights can be generated that can answer more question and bring more solution for that company.

Thank you for your time hope you have liked the report and the solution. 




# Kickstarting with Excel

## Overview of Project
The project is to perform analysis on Kickstarter campaign data to uncover trends

### Purpose
The purpose of the analysis is to assist Louise understand how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges
In order to determine how various campaigns managed in relation to their launch dates and their funding goals, I utilized a pivot table and the function, “COUNTIFs” to filter, collect, and sort necessary data to eventually create two line graphs.  The pivot table consisted of showcasing the outcome labels, “successful, failed, and canceled,” under the columns section and the months under the rows section.  The extracted data highlighted the theater outcomes based by the launch date.  To examine the percentage of campaign outcomes based on fundraiser goals, I used the function, “COUNTIFS” to collect and sort the outcome labels and data. The data was organized to highlight the number and percentage of successful, failed and canceled projects. 

I encountered a challenge while creating my "Theater Outcomes Based by Launch Date" chart as the "Row Labels" was showing the years instead of the months. It took several attempts, but I was able to group the "Row Labels" to instead show the months of the year.

### Theater Outcomes Based By Launch Date Chart
![date](Theater%20Outcomes%20vs%20Launch.png)

### Outcomes Based on Goals Chart
![goals](Outcomes%20vs%20Goals.png)

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
The month that launched the most successful Kickstarter Theater campaigns was May. The month of December showed that it had the least number of launched campaigns (n=37) while also having roughly the same number of failed campaigns (n=35).

- What can you conclude about the Outcomes based on Goals?
Based on the outcome percentages, play campaigns with a goal that is equal or less than $5,000 has a greater chance of being successfully funded. 

- What are some limitations of this dataset?
A limitation that may have occurred is that the parent category, “theater,” which consists of musicals, plays, and spaces, was used to review the campaign outcomes based by launch date, instead of filtering to the subcategory, "plays."  Additionally, a limitation could be that the plays were not filtered to a specific country, in which may skew and/or conflate the data that is necessary to help guide the success of Louise's campaign. 

- What are some other possible tables and/or graphs that we could create?
A possible pivot table and chart to create is to showcase “play outcomes based on launch date,” compared to "theater outcomes by launch date." 

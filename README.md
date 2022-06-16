# Kickstarting with Excel
Analysis of Kickstarter data to be submitted for Challenge #1 of the MSU Data Analytics Course
## Overview of Project

### Purpose
This analysis is designed to examine different Kickstarter campaigns by outcome and based on launch date and goals.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
This analysis was performed by creating a pivot table which highlighted the results of all Kickstarter campaigns (successful, failed, or canceled) based on month of the year. A line graph was then created to display the results of the pivot table, as shown below.![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/107012216/174175499-61088cdd-532a-40cf-a886-9abadddd3ef1.png)

### Analysis of Outcomes Based on Goals
This analysis was performed by creating a table with goal ranges from less than $1,000 to more than $50,000. The countifs function was used to determine the number of successful, failed, and canceled play campaigns based on the criteria above. These results were turned into percentages and used to create the line graph shown below.![Outcomes_vs_Goals](https://user-images.githubusercontent.com/107012216/174178798-407931a7-8a4e-40b4-86c9-10074cf4c3b1.png)

### Challenges and Difficulties Encountered
The only challenge was encountered while using the countifs function, which is long and difficult to format. Trial and error was used to find the correct syntax for the formula by filtering certain data, including the outcome result, goal range, and campaign subcategory.
## Results

Using the outcomes based on launch date line graph, it can be concluded that the most successful time of year to create a campaign is May-July. Additionally, the worst time to start a campaign is at the end of the year, with December having the least amount of successful campaigns.

Using the outcomes based on goal line graph, it can be concluded that a goal of more than $45,000 results in an extremely small percentage of successful campaigns. Additionally, the $1,000 to $10,000 range resulted in a higher percentage of successful campaigns, indicating it might be better to have a smaller goal for a Kickstarter.

A limitation of the dataset is its size, as this is not the entire scope of all Kickstarter campaigns, so the results can only be taken at face value. 

Additional interpretations of the data that could have been created include outcomes based on country, outcomes based on amount of backers, and outcomes based on year.

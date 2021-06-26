# Kickstarter Analysis


## Overview of Project

Louise is a promising playright who plans to start a crowdfunding campaign to help fund her play "Fever".  The play will have an estimated budget of $10,000.  Using the Kickstarter datset she would like to understand the relationship between launch dates and their funding goals.

### Purpose

With the information extracted, utilizing excel, the analysis will help Louise understand the factors for successful fundraising.  These factors can be used by Louise to help her on the way to launching a successful crowdfunding campaign.

The data for analysis was used in the following excel file:

[Kickstarter_Challenge.xlsx](https://github.com/mfreel14/kickstarter-analysis/files/6719491/Kickstarter_Challenge.xlsx)

## Analysis and Challenges

Analysis of Outcomes Based on Launch Date

The analysis of Outcomes Based on Launch dates involved creating a new column in our kickstarter dataset for "Years".  In the new column, the excel YEAR()function was used to grab the information from the date created conversion column.  

The next step was to create a pivot table showing Successful, Failed and Canceled campaigns by months through the years.  Using a filter in the "Parent Category" the data was made to show only "theater".  The campaign outcomes were sorted in descending order with "successful" being our first column.  

A line chart was then created with our filtered data showing the number of campaings correlated with their success, failed and canceled rate.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/691355/123500475-55a8a780-d60c-11eb-9408-04ef23de0874.png)

## Analysis of Outcomes Based on Goals

The start for analysis of Outcomes Based on Goals involved creating a new table with our goal ranges.  The dollar-amount ranges were used to group projects based on their goal amount.

The COUNTIFS() was used to populate the number of successful, failed and canceled "plays" based on their goal amounts.  A percentage was then calculated for the number of succesful, failed and canceled plays.

A chart was created for this data to show the goal-amount ranges and the percentage of successful, failed and canceled projects.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/691355/123500528-be901f80-d60c-11eb-90ea-96d9fbc8ba24.png)

### Challenges and Difficulties Encountered



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

1.  The average success rate for launching a campaign in kickstarter for plays is 61%.

2.  The most successful month for campaigns was May with 111 successful campaigns and 67% of campaigns receving funding.  The least      successful month for campaigns was December with 37 successful campaigns and only 49% receiving funding.

<img width="602" alt="Theater_Outcomes_Percent" src="https://user-images.githubusercontent.com/691355/123500640-9654f080-d60d-11eb-8038-b8f1959ac843.png">


- What can you conclude about the Outcomes based on Goals?

1. Our outcomes based on goal analysis tells us that project goals with ranges between $10,000 and $14,9999 have a 54% chance at being successful.  Decreasing her campaign amount between $5,000 - $9,999 only increases the success by 1% (55%).  Increasing the amount to 15,000- $19,999 decreases her success rate by 4% (50%).

<img width="624" alt="Outcome_Ranges" src="https://user-images.githubusercontent.com/691355/123500649-a1a81c00-d60d-11eb-9012-55ee8cd5fcf6.png">

- What are some limitations of this dataset?

There are other factors that can influence the success of a kickstarter campaign.  The data doesn't account for accompanying marketing campaigns and the role it played in the success.  The data also doesn't further breakdown which category of plays is most successful.  It would be of interest to see if there's a higher success rate with a specific play and weather it's a drama, comedy or romance.

- What are some other possible tables and/or graphs that we could create?

Line Graph of year over year to see which years were the most successful.  This could help determine if the success rate of campaigns year over year is increasing or decreasing in relatation to the play category.


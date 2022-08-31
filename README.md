# Kickstarting with Excel

## Overview

### Overview of Project

The purpose of this project was to help Louise understand how her campaign for the play Fever, compared to other campaigns regarding their launch dates and funding goals. Even though she failed to reach her fundraising goal, this analysis will help her understand how to set effective goals and launch dates in future campaigns.


## Analysis

### Analysis of Outcomes Based on Launch Date

I started my analysis by using the “Year” function to create a column for year, based on the “Date Created Conversion” column. This provided additional filtering capabilities which I knew I would need going forward. I then used a pivot table which included filters for “Parent Category” and “Year”, in addition to the totals for the number of successful outcomes by month. I also made a line graph based on this table, which illustrates the number of outcomes and their results per month. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111243284/187776608-97cfb9db-9150-4492-935c-f1a2fc78fb0e.png)



### Analysis of Outcomes Based on Goals

  Next, I created a table for the outcomes based on goals and this required me to use the “Countifs” function to break down the goals by outcomes and ranges. I also calculated percentages for each outcome (successful, failed, canceled) by using the “Sum” function to get the total number of projects, and then dividing each outcome into the total. Once I completed these calculations, I created another line graph which shows the percentage of all three outcomes based on their goal ranges. This concluded my analysis for the Kickstarter Project.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111243284/187777151-06ff3f83-5d89-4db3-8965-15f9ae346c26.png)



### Challenges

The main challenge I faced with this project was understanding how to use the “Countifs” function. I really had to pay attention to the conditions I was using because it was easy to make a mistake. I also found it very tedious to set multiple conditions and I would try to make this process more efficient by using anchors ($) for my formulas.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	1. Based on the “Theater Outcomes by Launch Date”, I would encourage Louise to launch her campaign in May, since this month is when the most successful campaigns occur. 
	2. I would also caution her not to wait until June, because the number of successful campaigns declines until September.

- What can you conclude about the Outcomes based on Goals?

	Based on the “Outcomes by Goals”, this type of campaign can be successful with a goal of less than $1,000. This should be encouraging for Louise since her chances of success are greater at a lower cost.

- What are some limitations of this dataset?

	One limitation I noticed was that the dataset does not include information about the Genre of each play. While some plays have a description, which includes comedy and drama, knowing the Genre of each play will help understand who Louise’s target audience should be. Maybe Comedies are more successful than Tragedies, and this information is important in determining a potential outcome for our play. It would also be helpful to see the ratings for each play. Maybe there is a correlation with positive ratings and successful campaigns, or it may not matter. This would also provide a better understanding of what it takes to run a successful campaign.

- What are some other possible tables and/or graphs that we could create?

	I would recommend creating a graph showing theater outcomes by country, which would allow Louise to see how the plays are performing based on the Country. It could be that most successful plays occur in England instead of the U.S, and this is information that Louise would need to know. 

# Kickstarting with Excel

## Overview of Project
In this project, I analyze how both, the goal of a Kickstarter campaign and the launch date of the campaign, are related to the outcome of the campaign.
--
### Purpose
I am trying to determine if there are optimal contribution goals and the best times to launch Kickstarter campaigns to maximize the chances of having a successful campaign.
This analysis could also be used to help explain why a campaign may not have been as successful as anticipated. This specific analysis was done with data from Kickstarter campaigns 
for plays in a theater.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To analzye the how the Launch date may effect the outcome of a Kickstarter campaign, I used the data of Kickstarter campaigns that occurred between the years 2009 and 2017. In my analysis, I filtered out any
campaigns that were not in the Theater category. I grouped the data by months. I categorized the outcomes of the campaigns into three categories, successful, failed and canceled (I did not
include campagins that were currently live). A quick look at Theater Campaign outcomes based on Launch Date tells us that the most successful campaigns are launched in May, June, and July. (see chart below): <img src = "https://github.com/AaronAKTX/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png.png">

### Analysis of Outcomes Based on Goals
To analyze how the goal may affect the outcome of a Kickstarter campaign, I again used the data of Kickstarter campaigns that occurred between the years 2009 and 2017. In my analysis, I filtered out any
campaigns that were not specifically for plays. I organized the data into groups based on how much money the contribution goal of the campaign was. Starting with any campaign that had less than a $1000 goal and grouping the subsequent groups in increments of $5000.
By graphing three lines of data, one for Successful campaigns, one for failed campaigns, and one for canceled campaigns,(I did not include campaigns that were currently live) I tried to display any correlation that may exist between the contribution goal and the outcome of the campaign. The chart may not be as informative as it could be as the number of campaigns drops below a relevant data set as the contribution goal increases. However, it does display what would be expected, that as the goal increases, the success rate of the campaign goes down.
see chart below)(note: there is an increase in success rate for campaigns with goals between $35000 and $40000 but there were only a total of 6 campaigns this size so it's not clear that this increase is significant) Also, because there were no canceled play campaigns during this time, the lines of successful campaigns and failed campaigns are mirror images of each other.:

<img src = "https://github.com/AaronAKTX/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png", width = "100">

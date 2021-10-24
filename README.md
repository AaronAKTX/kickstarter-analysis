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

<img src = "https://github.com/AaronAKTX/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png">

### Challenges and Difficulties Encountered
I did not run into too many challenges with the actual class work. I needed to learn the CountIF excel function and also trying to copy a cell values from one column to another without excel updating the column in the function was frustrating. I actually updated each individual cell in the table I created when using the CountIF function before figuring out how to use the absolute cell values in the function.  I also needed to become more comfortable with the use of pivot tables and creation of graphs based on pivot tables. 
In a more general sense, the analysis of the Kickstarter data has a few challenges. There are a lot of unknowns, like who the campaign donation requests are being sent to and how that list varies and affects the outcome. Filtering the campaigns to only include specific categories or subcategories is helpful but it often drops the sample size down so much that the results are easily skewed by a small number of extreme values. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Looking at the results of the analysis of outcomes based on launch date, I think you can draw the conclusion that campaigns that begin in May, June and July are the most successful. You can also clearly see that campaigns launched in December have the lowest success rate. It's notable also that the number of total campaigns is the highest in the spring and summer.  The chart below displays the percentage of success of Kickstarter campaigns for plays. The blue line on the top shows the percentage of success, it suggests that campaigns started in May have the highest chance of success while the campaigns starting in December have the worst odds. It also shows that the late spring and summer seem to be the best times to launch a kickstarter campaign.
<img src = "https://github.com/AaronAKTX/kickstarter-analysis/blob/main/resources/Campaign_Success_by_Month.png">
- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?

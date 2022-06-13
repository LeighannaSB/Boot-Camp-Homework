# Theater Kickstarter Analysis

## Overview
The purpose of this project was to determine the factors that contribute to successful and unsuccesful kickstarter campaigns.  The project pulled in kickstarter data from thousands of campaigns across the world and drilled down to focus on theater play kickstarters to determine the best course of action for starting a new kickstarter campaign for a theater play.  

## Data Analysis
The data set includes 1067 theater play kickstarter campaigns with goals ranging from $1.00 to $200,000.00 and that ultimately raised $0 to $100,824.00. The data set provides some small immediate challenges in how the data was presented. An example includes the categories of the kickstarters not being as specific as needed for this analysis; the original category presented was "Theater" and this included kickstarters for plays but also musicals and campaigns for theater spaces. In excel we were able to break these out into parent categories and subcategories in order to focus on the "play" subcategory. Another example is that the goal amount and pledged amount for each kickstarter was presented in their own columns in the file but there was no quick way to view all the campaigns that successfully met or failed meeting their goal. Using conditional formatting in excel we were able to use the "goal" and "pledged" columns data to create a new column confirming whether each kickstarter successfully met their goal, failed to meet their goal, was canceled, or is currently a live campaign working towards its goal. 

**Success by Launch Date**

Once the theater play data was broken out by the success of the kickstarter we were able to create a pivot table to easily show how many kickstarters were successful, failed, or were canceled by the date the campaign was launched. This data is demonstrated below using a line graph which shows that the month with the highest number of successful campaigns was May and the month with the lowest number of successful campaigns was December. 
![This is an image](![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/107161421/173260505-f82ad016-b050-4851-9e16-b42a6a8b1ac7.png)

**Success by Goals**

Using the COUNTIFS function in excel we were able to break out the number of succesful, failed, and canceled theater play kickstarters based on their fundraising goals. The highest percentage of successful campaigns were those with goals under $1000 coming in with a 75.81% success rate (141/186 campaigns). The $1000 to $4999 goal category came in at a close second with a 72.66% success rate (388/534 campaigns). This analysis for each goal category up to $50,000+ is demonstrated using the line graph below.
![This is an image](![Outcomes_vs_Goals](https://user-images.githubusercontent.com/107161421/173261132-a296a287-c6f6-44e8-87c7-703d3d77c8b0.png)

## Summary of Results
The analysis in the Outcomes by Lauch Date table show that historically the best dates to launch to launch a successful theater play kickstarter would be in May or June as those months had the top two totals of successful campaigns; 111 and 100 campaigns respectfully. This works out to a 67% success rate for kickstarter campaigns launchedin May and a 65% success rate for June campaigns. This analysis also shows it would be the least likely to have a successful campaign that is launched in December as this is the month with the fewest successful kickstarters (only 37 total successful campaigns, a 17 point drop from the next lowest month of November) and a success rate of only 49%. The analysis in the Outcomes Based on Goal table also shows the best chance of lauching a successful campaign is to keep the fundraising goal under $1000 although a campaign with a goal in the $1000 to $4999 range would only have a 3% less chance of being sucessful. 

**Potential Limitations and Future Analysis**

This dataset contains a small number of kickstarters with goals that are significantly lower or higher than the majority of the dataset. This could potentially be limiting the analysis but a box and whisker chart could be added to demonstrate any outliers in the dataset. The most recent launch date for a kickstarter in this dataset was in 2017. The lack of more recent data could be limiting the accuracy of the findings when applied to a new campaign launching in 2022. It could be beneficial to secure a more recent dataset to compare to given the social and financial changes that have occured on a global scale in the years following 2017. 


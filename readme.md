# Kickstarting with Excel
Louise and the play "Fever"

## Overview of Project
This project is to help Louise determine how to go about setting up her fund-raising for a play, Fever, that she wants to produce.  Louise wants to do start a kickstarter campaign to help raise the money for the play, and has a lot of data on how other events have fared in raising money for a project.

### Purpose
The purpose of this analysis is to help determine when Louise should start her kickstarter campaign, as well as a target for the amount of funds she should raise.  She has an extensive list of data for different types of fund-raising campaigns, which includes how much they wanted to raise, how much they raised, where the campaign happened, what type of endeavor the campaign was for, and when they launched the campaign.  We focused on the campaigns that raised money for the theater in the subspace plays.

## Analysis and Challenges
There were 2 different analysis that we ran, one based on launch date, the other based on the fund-raising goal.

### Analysis of Outcomes Based on Launch Date
This analysis was done on all campaigns in the theater space, not only on those done in the subcategory of "Plays."  We looked at how a campaign was either successful, failed, or canceled based on the month the campaign was started.  The 2 main pieces that came out of this was a pivot table, and a pivot chart.  The pivot chart is displayed as Theatre Outcomes vs Launch.

### Analysis of Outcomes Based on Goals
This analysis was done specifically on the Plays subcategory in the theater space.  We calculated how different play campaigns did based on their goal.  We looked at 12 different ranges of monetary goals, and determined a success as a campaign that met or exceeded the goal, and a failure as a campaign that did not meet the goal.  We also looked at campaigns that were canceled, but for the subgroup that we analyzed we found that there were not campaigns that were canceled.

### Challenges and Difficulties Encountered
There were 2 main difficulties that we didn't look at which could limit the conclusions that we report.  Those 2 limits were where was the location of the campaign, and how many backers the campaign had.  This was data available and could have some influence on if a campaign was a success or failure.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	- The first conclusion I saw was that it appeared that the most successful campaigns occurred in May and June.  While I believe there are limitations that I will talk about in conclusion 2, those 2 months did produce the largest number of successful campaigns.
	- The second conclusion I came to was that almost every month had the same chance of having a successful campaign, other than December.  As mentioned in conclusion one, the months May and June seem to be the most successful based on number of successful campaigns, but it should be pointed out that there were more total campaigns in those time frames so their successes are not as skewed as one might think.  While May and June both have a 65 to 67 % success rate, there are many other months that have a success rate in the 60% range.  In fact, the months of February, March, April, May, June, July, September, and November all have success rate greater than 60%.
	
- What can you conclude about the Outcomes based on Goals?
	- I concluded that Louise should keep her fund-raising goal under $15,000, but to be even more successful, she should keep it under $5,000.  A goal in the range of $5,000 to $15,000 had a success rate of about 55%, but if the goal was less than $5,000 there was a success rate of closer to 75%.  While it is better than even odds in the $5,000 to $15,000 range, that is a slim margin above 50/50.  One thing to point out is that there appear to be a few outliers in this data.  The range of $35,000 to $45,000 showed a success rate at 66%, but it should be worth noting that these ranges had only a total of 9 campaigns, and this sample size is too small to confidently use the Law of large numbers from statistics to state that the outcome is approaching the correct mean.

- What are some limitations of this dataset?
	- One of the main limitation here is that we are not looking at how the donors are being found, and how much each donor contributes.  Also, we did not look at the types of plays.  For instance, were there certain genres, such as musicals, comedies, or dramas that did better than others? 

- What are some other possible tables and/or graphs that we could create?
	- I would have also looked at the average amount that any backer gave for a play, as well as where the campaign was run.  In addition, we did not look at how successful a successful campaign was, or how close to success a failed campaign was.  For instance, if all successful campaigns with a goal less than $5,000 achieved triple their goal, and campaigns with a goal $5,000 to $10,000 simply met their goal, then it might be better to keep the goal lower to raise more funds for the play.

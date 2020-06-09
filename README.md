### An Analysis of Kickstarter Campaigns

This data analysis project is prepared to assist playwrite Louise on selecting the most effective strategy for her campaign by revealing trends and insights from the past Kickstarter campaigns data. Louise wants to start a crowdfunding campaign to help fund her play Fever; her estimated budget is $10,000. The analysis is completed using MS Excel analytical tools such as PivotTable, PivotChart, VLOOKUP, Descriptive Statistics and COUNTIFS.   

---
Let's start by looking at the overall summary of Kickstarter campaign data visualized by the Parent Category. The data is quickly revealing that *theater/plays* category is the most popular in the United States.

![Chart 1 - Parent Category Outcome](https://github.com/AnnaS0272/kickstarter-analysis/blob/master/Chart%201%20-%20Parent%20Category%20Outcome.png)

We further examine the relationship of plays with other subcategories within the United States. Plays are very popular amongst all subcategories and, seemingly, have a high success rate. That's certainly good news for Louise as she is preparing to campaign in this subcategory. But we can also see that failure rates are pretty high too, accounting for almost a half of all plays. Given such dynamics, we need to better understand what makes a theatrical play campaign successful. 

![Chart 3 - Subcategory Statistics US](https://github.com/AnnaS0272/kickstarter-analysis/blob/master/Chart%203%20-%20Subcategory%20Statistics%20US.png)

If we examine whether the month of the year makes any impact on the success of the campaign, it is obvious that campaigns started in May are the most successful. It is likely connected with the upcoming summer break, more relaxed schedules and picking up interest of the public in attending cultural events such as plays.

![Chart 4 - Outcomes based on launch date](https://github.com/AnnaS0272/kickstarter-analysis/blob/master/Chart%204%20-%20Outcomes%20based%20on%20launch%20date.png)

The data is also revealing that succesful campaigns were run for less than 30 days. Therefore, campaign duration should be taken into account as well.

![Chart 6 - Average Duration Plays](https://github.com/AnnaS0272/kickstarter-analysis/blob/master/Chart%206%20-%20Average%20Duration%20Plays.png)

Finally, we need to look at what the financial goal and pledged data reveals. As we can see from the summary table below, average succesful campaign is  $5,000 which is almost twice less than what Louise has planned for, therefore it would be wise to target a lower range. Similarly, high standard deviations for failed points to the fact that there were some projects with really high goals and they were not successful.

![Descriptive Statistics Plays](https://github.com/AnnaS0272/kickstarter-analysis/blob/master/Descriptive%20Statistics%20Plays.png)

* ***Recommendation No. 1 - Plan to start your campaign in May.***
* ***Recommendation No. 2 - Run your campaign for max 4 weeks.***
* ***Recommendation No. 3 - Target campaign cost between $4,000 - $6,000.***
---
### Module 1 Challenge

When further examining the relationship between the Outcome and the Goal, we can see the following trends emerging. As the Goal amount is increasing the success percentage is gradually declining and the failure percentage is rising. We can observe some reversal of the trend in the middle and towards the end, signifying that some high value campaigns for plays do become successful; however the number of those projects are low, and the data may be biased by those small number of samples that are not statistically significant. The ultimate pattern remains the same: with the rising Goal amount, the success percentage is declining. It is also evident from the data that no play campaigns get canceled, possibly supporting the strong demand for play campaigns and positive expectations. 

![Chart 5 - Outcomes Based On Goal](https://github.com/AnnaS0272/kickstarter-analysis/blob/master/Chart%205%20-%20Outcomes%20Based%20On%20Goal.png)

Looking again at the launch date for all theater campaigns, the data reveals that May is the most succesful month for theater campaigns, however, we can also see failures pick up in May too. That can possibly be caused by competing projects, e.g., plays are competing with musicals. If Louise is considering launching a musical campaign as well, she should be aware of this potential competition. It looks like October can also be a good month for launching a musical campaign. We notice a pick up in cancelations in January likely due to the start of the year and new priorities, and June as interest slows down after busy month of May.

![Chart 4 - Outcomes based on Launch Date-ALL ](https://github.com/AnnaS0272/kickstarter-analysis/blob/master/Chart%204%20-%20Outcomes%20based%20on%20Launch%20Date-ALL.png)



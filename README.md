# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

## Introduction
The following analysis is to assist a playwrite. Our friend Louise will be producing a new project called 'Fever' with a budget of $10,000 and has asked us to analyze other crowdfunding projects to ensure hers obtains the greatest success. We will be looking at the trends of both successes and failures in great detail to formulate the best approach into the business for our friend, so that she breaks a leg when her show becomes LIVE and continues to do so for many successful show nights!

In this analysis, we will take an in depth view of the overall trends associated with the data provided as well as the trends specifically pertaining to Louise's specialized industry. We will answer her important question as to length of successful campaigns, seasons of successful campaigns, trend of success with Louise's planned approach of campaigning for a 10,000 budget, statistical components of our research, results of analyzing the success of Edinburgh plays, and finally, the chance of success and suggestions of approach if Louise attempts to enter into the theater industry of Great Britain with plays. We will then conclude with observations and suggestions to make a successful campaign, both in the short term, and in the long term.

## Industry Overview
In the Kickstarter campaigns, each campaign belongs to both a Parent Category and a Subcategory. Parent categories is a general list of what industry each campagin belongs to, and the subcategories is a more specific type of category within that industry. Similar to cable channels, how there is a channel for sports and a channel for movies. Sports have subcategories such as football, soccer, and rugby sports, while the movie channel has romance, action, and drama movies. Let's take a closer look into the Parent Category and Subcategories of Kickstarter. 

### Parent Category
As we take a general overview to the Kickstarter campaigns for all parent categories, we can see in the chart below that music and theater are the most successful campaigns of all. 

![](Images/Parent_Category_Outcomes.png)

Between theater and music, music does run fewer campaigns, but even so, they both have about the similar success rates, but music has very little failed outcomes compared to that of theater. The theater industry almost has as many failures that successes, but successes are still significantly higher.

### Subcategory
Looking deeper into what type of theater performances make up the most campaigns and the most successful campaigns, it would be the subcategory of plays, demonstrated by the following chart:

![](Images/Subcategory_Outcomes.png)

As we can see, the subcategory of plays far exceed other subcategories both in both successes and failures. It appears to be the driving force of the entire Parent Category of Theater.

Now that we can visibly see how each Parent Category and Subcategory makes up all of the Kickstarter campaigns, we will now take a closer look into the Parent Category of theater and the Subcategories of Plays for our Play producing friend Louise and guide her to a successful Kickstarter campaign of her own using the data obtained from Kickstarter.


## In Depth Views of Data Trends

*Is the length of the fundraising campaign correlated with its success?*

In utilizing the data in the first table provided, it is shown that the average running time of the fundraising campaign was 29 days. For the failed US plays, the average campaign run was 34 days. Based on this table alone, it appears that the longer a campaign is run beyond 30 days does not improve the success of the campaign. The second table, the actual correlation table, gives us a better breakdown as to other variables that do play a part into a play's success or failure. 

![](./Images/US_Outcome_Plays.png)

### Campaign Days Correlation to Success via Pledge and Goal Relationship:
As we can see from the correlation table, the correlation of campaign days is 0.14 for successful plays against the variable of both the pledged amount and the goal amount of the campaign. In failed campaigns, its only 0.04 and 0.07, respectively. The correlation is very small that there just is not enough evidence to say that (as stated above) campaign days run affects a plays success/fail. 

![](./Images/Kickstarter_Correlation.png)

### Pledge and Goal Correlation to Success:
Upon looking at the correlations of the goals against the pledges under successful campaigns, the correlation is a strong 0.99. This demonstrates that there is great evidence of how relevant each variable is to one another. Upon looking at the failed plays, the correlation between the pledge and goal amounts is 0.05. This matches well with the earlier chart that points out that in successful plays, there is an average pledge amount of $5,602 where the goal was an average of $5,049. The pledges of the successful plays met the goal by 110% on average. In opposition, the failed plays had an average pledge amount of $563 of a $10,621 goal, hereby meeting only 5% of their Kickstarter goal. This gap is represented well by the 0.99 (successful) and 0.05 (failed) correlation between the pledge and goal variables in the table. Because there is evidence of a strong relationship between goals and pledges of successful plays and such a weak relationship of this in the failed plays, we can only assume that the relationship between the goals and pledges is highly relevent to the outcome of plays.

### Backers_Count Correlation to Success via Goal Relationship:
The last variable we will observe is the backers_count. This variable represents the people who donated to the kickstarter campaign. As we can see in the above chart, with successful plays, the kickstarter campaign did meet 111% of their goal with an average of 63 backers contributing. This success and relatively high number of backers is shown in the correlation table. Here we can see a correlation of 0.74 between backers_count and goal, as well as a 0.80 correlation between the backers_count and the pledged variables.We can make note that the average goal is, again, around $5000. The failed plays, on the otherhand that met only 5% on goals, which had an average of 8 backers. We can note here that failed plays had an average goal of about $10,000.

On the otherhand, in failed plays, revisiting how only 5% of their average $10,000 goal was met (about $800) with only 8 backers to support, we can see this relationship play out in the correlation table as well. The relationship of the backers_count with the pledged variable is an 0.89, showing that there is without a doubt a strong relationship between the number of backers and the amount of pledges - that would be the 8 backers to $800 in pledges. Yet, when observing the relationship between the backers_count and goal variables, we see that in the correlation chart is shown to be only 0.013. This indicates a very weak relationship, demonstrating the large gap between the 8 backers and the $10,000 average goal of plays. 

Upon looking at the evidence, we can conclude that a strong relationship must exists both between the pledges and goals as well as backers and goals. Although this is so, it does appear that the biggest indicator of success is the relationship between the backers and the goals. If that relationship is strong, then it is a strong indication that success is not too far behind. 


*In what season were the campaigns the most successful?*

Summer was the most successful season for the play campaigns. The month of May was the overall most successful, followed by June, July, and August. Unfortunately, those same months were the months of the highest failure rates as well as shown by the following chart:

![](./Images/Outcomes%20Based%20on%20Launch%20Date.png)


### Kickstarters Campaign Statistical Components:

![](./Images/Descriptive_Statistics.png)

The statistical components tells us: 
- The mean of each distribution is in the 3rd quartile and the data follows similar distributions in each subset
- The standard deviation is larger than the mean, which mean that everything below the mean is considered "close" to the center
- Some large values are driving all of these distributions. The standard deviations are all roughly twice the IQR in each distribution, except in the failed Kickstarters, where the standard deviation is closer to three times the IQR. There must be some failed Kickstarters with really high goals!


## Edinburgh Plays

Louise also mentioned that she wanted to know how the Edinburgh Festival Fringe plays were funded. Based on the information obtained, all of the Edinburgh plays were quite successful. They all had an average goal of $2100. Their average pledge exceeded that amount at about $2384. In addition to this, the average donation was $40 and the average number of backers was $62. 

![](./Images/Edinburgh%20Research.png)


## Great Britain's Theater Market

Louise mentions of her interest in GB's theater market and how she intends to have a budget of 4000 pounds. 

Upon analyzing the data through the use of Box Plots, it shows us that, yes, the mean goal is 4000 pounds. These 4000 pounds are in fact outside of the range of outliers for the amount pledges. It will be ideal for Louise to get the play produces for less than 4000 pounds. Half of the campaign goals are less than 2,000 pounds, which is just over the 3rd quartile for amounts pledged, and 25% of the campaign goals have no pledged amount at all as demonstrated by the lower quartile of pledges beginning on the x-axis. 

![](./Images/GBTheaterFund.png)

As a result, in regard to Great Britain's theater market, it appears to be high risk. If Louise were to proceed with entering the market, she should stick to a budget of no more than 2,000 pounds because this budget appears to be the blueprint of the plays that did survive in this country.


## In Conclusion:

*For Short Term Success*

If Louise wants to produce her play Fever with a budget of $10,000 and no less, she increases her chances of success if she:
1. Considers running her play in the summer. May is the ideal month, followed by June and July
2. Considers advertising her Kickstarter campaign to receive an average of 100 backers, and the campaign run needs to be complete within 30 days
3. Considers advertising for backers externally of the campaign to meet the volume of backers necessary to achieve her financial goal
4. Considers lowering her overall budget to possibly $5,000 or lower to as little as $2,000 to mimick the success of the Edinburgh Festival Fringe plays 


*For Long Term Success*

By now, we understand that based on the data, the number of backers is the key to meeting and exceeding budget goals. Meeting and exceeding budget goals is necessary to be identified as "successful". Repeatedly within the data, it is demonstrated that it took many backers to make a successful play. That being said, Louise could also consider significantly lowering her budget for the play. The lower the budget, the easier it is to obtain enough backers based on curiosity alone in order to fund the play, especially if she is a playwrite without much of a name behind her. 

The average budget of successful plays was $5,000, and the average pledge did exceed this. Lowering her budget could help bring her more immediate success as she continues to build her name in US plays. It is likely that for the higher budgeted plays, many of the individuals pledging are repeat sponsors, versus first time sponsors. If Louise shows she can run a successful play with a minimum budget - proving that she can do more with less, then by the time she runs her next play, she will have acquired some faithful backers to exceed the budget of her next play. Through building up these repeat backers, in a matter of time, she will have enough backers plus some to run a much higher budgeted campaign and have enough volume of repeat backers behind her to exceed even her highest budget and for repeated support to future plays she is to write. The volume of backers, "repeat" backers, is key.

We look forward to the results of Louise's Kickstarter campaign!

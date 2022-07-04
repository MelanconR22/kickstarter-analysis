# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends
## Overview of Project:
This analysis project was brought to me by Louise, who is an up and coming playwrite.  Louise found and plans to use a crowdfunding platform called Kickstarter which exists to help bring creative projects to life by allowing others to help fund creative projects.  She plans to raise funds to launch a play that she has written called, "Fever".  Louise asked for help in identifying factors that led to other campaigns being successful as well as factors that led to unsuccessful campaigns.  She created a budget for her play and needed to raise $12,000 to see her work come to life.

### Purpose:
Upon reviewing the data from Kickstarter campaigns, Louise came close to raising her campaign fundraising goal.  She is now curious how launch dates and funding goals affect the success of a campaign.  This analysis will take a look at the data to gain some insight into the questions that Louise has about launch dates and funding goals.  

## Analysis and Challenges:

The dataset that was provided for this project contained information relating to just over 4,100 crowdfunding campaigns that are using Kickstarter to raise funds.  The dataset provided information on the funding goal of each campaign as well as the funding amount raised.  There were campaigns from all over the world and also in a wide variety of categories.  The categories were divided into fields such as film, music, games, technology, and theater among others.  The dataset also provided information about the launch date and number of backers who contributed to the campaign.  

The dataset provided information that allowed further insight by calculating the percentage funded as well as average donation amount.  The categories were broken out further into subcategories so that we coul drill down the data to gain insights from theater campaigns for Louis. The theater campaigns were further filtered to show only campaigns in the United States instead of globally.  There were a total of 912 theater campaigns with 525 successful campaigns for a success rate of 57.6%.  The data was then analyzed by the play subcategory which resulted in 671 total play campaigns of which 412 or 61.4% were successful in raising their goal for funding.       
### Challenges and Difficulties Encountered
Being new to data analytics, I encountered some challenges when beginning this project.  

### Analysis of Outcomes Based on Launch Date
##### The following chart shows the Outcomes Based on Launch Date:
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/107599510/177086201-17850191-b754-4416-9840-459015a0798a.png)

The graph was compiled of all Theater campaigns for all years and is divided into number of campaigns launched per month.  The data is then seperated by their outcomes of being successful, failed, or cancelled.  There were a total of 1369 Theater campaigns worldwide of which 839 or 61.3% of the campaigns were successful.  The month of May had the most number of campaigns (166) with the highest number of successful campaigns (111) or 66.9% success rate.

### Analysis of Outcomes Based on Goals
##### The following chart shows the Outcomes Based on Goals:
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/107599510/177090858-cad2f424-7a5b-4bd2-8a2a-26adcd71f422.png)

The data provided in the outcomes based on goals chart shows how many successful, failed, or cancelled campaigns there were for a given funding goal range.

I believe it is important to take a deeper look at the data in order to make sense of this graph.  The graph lines for percentage successful and percentage failed are inverse.  This is due to having 0 cancelled campaigns in this data set and the fact that we are looking at the two as a percentage against each other. In the data for this chart, there were a total of 1,047 campaigns listed as successful, failed, or cancelled for the subcategory of plays.  The sum of the total number of campaigns that had a funding goal of less than $10,000 is 889 or 84.9%.  This explains why the first half of the chart shows gradual movement while the second half of the chart is a bit more erratic.

##### The following chart provides a visual representation of the percentage of successful vs failed campaigns for each funding goal:
![Outcome_Percentages](https://user-images.githubusercontent.com/107599510/177200791-288c59df-de78-46ba-9625-1db5ba0fb131.png)

From a percentage successful standpoint, campaigns that aimed to raise less than $1,000 had the highest success rate at 75.8%.  The campiagns aiming to raise $1,000 to $4,999 were slightly less successful as the previous group with a success rate of 72.7%.  For the $5,000 to $9,999 and $10,000 to $14,999, the success rates droped to 55% and 54.2% respectively.  

##### The following chart shows the number of campaigns based on funding goal:
![Number_Campaigns_vs_Goal](https://user-images.githubusercontent.com/107599510/177201682-d8f6338d-03b7-4dff-9138-00385cd6cca4.png)

The information in this chart shows the concentration level of campaigns per funding goal group.  As is evidenced by this graph, the highest number of total projects (534) for any group fell in the $1,000 to $4,999 category and campaigns in this range enjoyed a 72.7% success rate.  I believe it is important for purposes of this project to understand the concentration levels at each funding goal group and to see how the success rate and number of projects decline as the funding goal increases.  It would make sense that campaigns asking for smaller amounts of funding would end up being more successful.  
  
## Results
#### What are two conclusions you can draw abou the Outcomes based on Launch Date?
There are two conclusions that stand out based on the results of data anlysis based on the outcomes by launch date.  The conclusions are that May has the most successful amount of campaigns while December has the fewest amount of successful campaigns.  June wasn't far behind May with a 65.4% success rate compared to 66.9% success rate for May, however, June had 13 fewer campaigns than in May. 

#### What can you conclude about the Outcomes based on Goals?
Looking at the data for outcomes based on goals, it is easy to conclude that there would be more campaigns raising $4,999 or less than campaigns asking to raise $5,000 or more.  It would also be logical to conclude that asking for a smaller funding goal would lead to a higher success rate.  For Louise's campgain, she had a fundraising goal of $12,000.  Based on the data for the play subcategory, campaigns similar to hers have historically had a success rate of 54.2%.  There were a total of 72 plays in the same goal range with 39 campaigns reaching their goal.   

#### What are some limitations of this dataset?
This dataset provides a wide range of valuable information and provides data to allow a data analyst to calculate percentages and ratios to help tell the story the data is showing us.  I would like to be able to analyze factors that would help lead to a conclusion on what makes May the most successful month and December the most unsuccessful month.  A person can come up with their own theories of why this is but the dataset doesn't provide information to examine this.  Additionally, I believe that some analysis on where the backers for the campgains lived would be useful.  It would allow a data analyst to determine if there was a proximity limit for people willing to donate funds for theater production.

#### What are some other possible tables and/or graphs that we could create?
The dataset provides enough data to create a graph that shows the number of successful campaigns per year.  This analysis would allow the conclusion to be drawn about whether or not crowdfunding has grown in popularity or is in a declining state.  Additionally, the dataset provides infomration where a bar graph could be used to illustrate the number of backers when compared to the size of the funding goal.  I believe this analysis would help Louise have a better understanding of the scale of her funding campaign.  If the data showed that successful plays needed a certain number of backers to reach a funding goal, then she would be equipped with further insight on how to market her fundraising campaign.  

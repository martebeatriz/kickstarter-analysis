# Analysis on Kickstarter Data
This analysis will look at two things:

1: the relationship between the outcomes of campaigns to their launch dates.  
2. the relationship between the outcomes of campaigns to the funding goals.


## Outcomes Based on Launch Date 
Using the Kickstarter data, the outcomes of **theater campaigns** were compared to their launch dates. Specifically, the following information was compiled and compared:
- The number of successful, failed, live, and canceled theater campaigns. 
- A breakdown of how many of the campaigns were successful, failed, still live, or canceled each month of the year. 
 ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/107375554/174402571-d060a995-9f01-46ac-9c93-50379f003368.png)

My analysis of this chart leads me to believe that the best time to start a fundraising campaign is during the month of May. The month of May had the highest percentage of successful campaigns.
 I would also say that the month of December is the worst time to start a campaign. It is the month with the lease percentage of successful campaigns- about 30-35% of those campaigns succeeded.

I didn’t have much trouble with this one. The chart in the module was useful as a point of reference. Thanks to that picture, I realized I forgot to clear a filter on the Kickstarter sheet. 


## Outcomes based on Goal
Using the Kickstarter data, the percentage of successful, failed, and canceled plays were analyzed based on the funding goal amount. The goal amounts were grouped in ranges and the amount of goals within the range were counted. 

 ![Outcomes Based on Goal](https://user-images.githubusercontent.com/107375554/174402700-48f784b9-37f0-41c7-9d49-bec93ca9f517.png)


Based on this chart I would say that the most successful campaigns have goals that are less than $5,000, those have nearly and 80% success rate. 

This task was a bit tedious because I had to go row by row in the first column and input the ranges. Then I dragged and extended box B2 into C2 and noticed a bunch of the criteria ranges changed. I remembered a trick from class where you add a “$” symbol before the column letter to keep the ranges frozen. Then I was able to continue dragging and extending to the left so that I only had to change the “failed” and “canceled” criteria.  


## Summary
A deeper dive can be taken regarding the failed the campaigns. 

For a better understanding of the data provided, I would recommend the use of a graph that looks at the failed campaigns and shows the percentage funded. If they were close to reaching their goals, they can then determine whether to relaunch a campaign with a lower goal. 

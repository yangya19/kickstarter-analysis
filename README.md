# Kickstarting with Excel

## Overview of Project
### Purpose
Performing analysis on kickstarter data, with focus on outcomes based on goals and outcomes based on launch date to uncover trends. Discover how different campaigns fared in relation to their launch dates and funding goals.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date

-Successful Campaigns Outcomes vs. Launch Date    

The line graph with launch date data in years 2009-2017, shows successful campaign outcomes reached their peak performance in May, followed by continuously declining till September. The outcomes have a slight recovery in September and October, then drastically decreased again to their lowest point in December.   


However, if we look into individual years we can discover the graph states inconsistency in trend. For example:    

Year 2010 - The peak performance month is in June, with an increase in its successful campaigns in November, reached the second-highest point in December; 
Year 2012 - The outcomes dropped quite a few from March and reached a low point in May, which contradicts the conclusion we earlier achieved;
Year 2013 - April became the best performing month through the year, follow by a decrease and reached a low point in May.   


-Failed Campaigns outcomes vs. Launch Date    

According to data in 2009-2017, failed campaigns outcomes sit in a stable range, and is not changed much through the year. Similar to what was discussed with outcomes for successful campaigns, there are some exceptions if we dive into year by year data:  

Year 2013 - The failed campaigns have significantly climbed up in September and dropped in November;
Year 2014 - The outcome increased from Feb till July, resulting in even more failed than succeeded campaigns in July, August and September;
Year 2015 - Failed campaigns outcomes have a decreasing trend through the year. 

In conclusion, with no other factors and variables given, it is inaccurate to conclude that launch date and campaigns outcomes are related.

### Analysis of Outcomes Based on Goals

From the line graph we can see, in general, campagin successful rate goes lower as the goals get bigger. In another word, the failure rate is higher as goals are bigger. 
It is not hard to notice that, there is a big increase in success rate in the goal range 35000 to 39999, 40000 to 44999. However, the sample size for these two criteria are quite small which may cause misleading conclusions. Another possible reason is that there are outliers in the original kickstarter data that we build analysis which may lead to less conclusive results. (refer to "kickstarter outliers" sheet and column V and W in "kickstarter" dataset)


### Challenges and Difficulties Encountered
My first time using countifs() formula in excel was challenging. I could not get the same graph as the instruction shows. After checking tutorials and videos on how to use countifs(), and by reviewing homework instructions I was finally able to get the proper result and get the same graph displayed on the module.

## Results

- What are two conclusions you can draw about the theatre Outcomes based on Launch Date?
May in general has the highest success rate for campaigns, and the success rate drops after June.
Cancelled campaigns are not affected by the launch date.


- What can you conclude about the Outcomes based on Goals?
The campaign success rate is in a negative relationship with goals. The bigger the goals, the less success rate campaign has.

- What are some limitations of this dataset?
This dataset does not tell enough variables to make accurate conclusions. Factors that can influence success rate includes economies, people's interest in TVs, technologies etc. There are many outliers in the dataset, which can mislead the analysis results.

- What are some other possible tables and/or graphs that we could create?
Outcomes vs. Campaign Duration, Average Donation vs. Type of the campaign

![2010 Outcome vs. launched date.png](https://github.com/yangya19/kickstarter-analysis/blob/main/2010%20outcomes.png)
![2012 Outcome vs. launched date.png](https://github.com/yangya19/kickstarter-analysis/blob/main/2012%20outcomes.png)
![2013 Outcome vs. launched date.png](https://github.com/yangya19/kickstarter-analysis/blob/main/2013%20outcomes.png)
![2014 Outcome vs. launched date.png](https://github.com/yangya19/kickstarter-analysis/blob/main/2014%20outcomes.png)
![2015 Outcome vs. launched date.png](https://github.com/yangya19/kickstarter-analysis/blob/main/2015%20outcomes.png)
![Outcomes_vs_Goals](https://github.com/yangya19/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)
![Theater_Outcomes_vs_Launch](https://github.com/yangya19/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)


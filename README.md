# Kickstarting with Excel

## Overview of Project
### Purpose
Performing analysis on kickstarter data, with focus on outcomes based on goals and outcomes based on launch date to uncover trends. Discover how different campaigns fared in relation to their launch dates and funding goals.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date

-Successful Campagins Outcomes vs. Launch Date    

The line graph with launch date data in years 2009-2017, shows sucessful campaign outcomes reached its peak performance in May, followed by countinously declining till September. The outcomes have a slightly recovery in September and October, then drastically decreased again to its lowest point in December.   


However, if we look into individual years we can discover the graph states inconsistency in trend. For example:    

Year 2010 - The peak performance month is in June, with an increase in its sucessful campaigns in November, reached the second highest point in December; 
Year 2012 - The outcomes dropped quite a few from March and reached a low point in May, which contradicts to the conclusion we earlier achieved;
Year 2013 - April became the best performing month through the year, follow by a decrease and reached to a low point in May.   


-Failed Campaigns outcomes vs. Launch Date    

According to data in 2009-2017, failed campaigns outcomes sit in a stable range, and is not changed much through the year. Similar to what was discussed with outcomes for successful campagins, there are some exceptions if we dive into year by year datas:  

Year 2013 - The failed campaigns has significantly climbed up in September and dropped in November;
Year 2014 - The outcome increased from Feb till July, resulting even more failed than successed campaigns in July, August and September;
Year 2015 - Failed campagins outcomes have a decreasing trend through the year. 

In conclusion, with no other factors and variables given, it is inaccurate to conclude that launch date and campaigns outcomes are related.

### Analysis of Outcomes Based on Goals

From the line graph we can see, in general, campagin sucessful rate goes lower as the goals gets bigger. In the other word, the failed rate is higher as goals is bigger. 
It is not hard to notice in goal range 35000 to 39999, 40000 to 44999 there is a big increase in sucessful rate. However,the sample size for these two criterias are quite small which may cause misleading conclusions.


### Challenges and Difficulties Encountered
My first time using countifs() formula in excel was challenging. I could not get the same graph as the instruction shows. After checking tutorials and videos on how to use countifs(), and by reviewing homework instructions I was finally able to get the proper result, and get the same graph displayed on the module.

## Results

- What are two conclusions you can draw about the theater Outcomes based on Launch Date?
May in general has the highest success rate for campagins, and the success rate drops after June.
Canceled campaigns is not affected by launch date.


- What can you conclude about the Outcomes based on Goals?
The campaign success rate is in negative relationship with goals. The bigger the goals, the less success rate campaign has.

- What are some limitations of this dataset?
This dataset does not tell enough variables to make accurate conclusions. Factors that can influence success rate includes economies, people's interested in TVs, technologies etc. 

- What are some other possible tables and/or graphs that we could create?
Outcomes vs. campaign duration
Outcomes vs. Type of the campaign (see which campaign is the most sucessful)


![2010 Outcome vs. launched date.png](https://github.com/yangya19/kickstarter-analysis/blob/main/2010%20outcomes.png)
![2012 Outcome vs. launched date.png](https://github.com/yangya19/kickstarter-analysis/blob/main/2012%20outcomes.png)
![2013 Outcome vs. launched date.png](https://github.com/yangya19/kickstarter-analysis/blob/main/2013%20outcomes.png)
![2014 Outcome vs. launched date.png](https://github.com/yangya19/kickstarter-analysis/blob/main/2014%20outcomes.png)
![2015 Outcome vs. launched date.png](https://github.com/yangya19/kickstarter-analysis/blob/main/2015%20outcomes.png)
![Outcomes_vs_Goals](https://github.com/yangya19/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)
![Theater_Outcomes_vs_Launch](https://github.com/yangya19/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)


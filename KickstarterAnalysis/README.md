# excel

**Background**

    Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

    Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success.

**Project**

    Modifying and analyzing the data of 4,000 past Kickstarter projects to uncover some market trends.
___

**Three conclusions we can draw about Kickstarter campaigns:**
1.	The theater category (parent) had the most campaigns overall, and both the most successful and failed campaigns. 
![](Images/Picture1.jpg)
2.	The plays sub-category, of the theater (parent) category also had the most campaigns overall, and both the most successful and failed campaigns as well. 
![](Images/Picture2.jpg)
3.	The number of campaigns is somewhat seasonal, peaking in the summer months for all years, with successful campaigns dropping off at the end of the calendar year. 
![](Images/Picture3.jpg)
<!-- 4. Missing data about the region of the campaign other than country and currency type that could be used to drilldown into regional differences. 
![](Images/Picture.jpg)
5. Missing data indicating the scale of effort to advertise or market the campaign that could be used to analyze what level of effort results in success. 
![](Images/Picture.jpg) -->

**Theater and plays are the most frequent Kickstarter campaigns with 1,000+ total**

![](Images/Picture6.jpg)

**Campaign Outcomes**

![](Images/Picture7.jpg)

![](Images/Picture8.jpg)


| Outcomes | Success | Fail | Total | text |
|---- | ---- | ---- | ---- | ----|
| Total | 2,185 | 1,530 | 3,715 |
| Mean	| 194	| 18    | 113   |
| Median    |	62|	4   | 25 | summarizes the data more meaningfully by showing that at least half of the successful campaigns have at least 62 backers, while at least half of failed campaigns has less than 4 backers. |
| Minimum   |	1|	0| 0 | makes sense that campaigns with 0 backers failed, at least 1 backer is necessary for a successful campaign |
| Maximum   |	26,457|	1,293| 26,457 | all failed campaigns had fewer than 1,293 backers
| Variance  |	713,167|	3,776| 388,862 | is higher in successful campaigns, and lower in failed campaigns which implies campaigns that more closely track the mean (average) number of backers have a higher failure rate. 
| Standard Deviation | 844 | 61 | 624 | higher in successful campaigns, and lower in failed campaigns, implying a larger range of number of backers increases the chances of success.

**Conclusion**
- Successful campaigns are more variable across the number of backers which makes sense because high variability indicates higher risk that may be accompanied by higher reward. It seems the failed campaigns adhere to a low variability, i.e. low risk model which leads to low reward.**


**Limitations**
- Missing demographic and marketing data.

What are some other possible tables and/or graphs that we could create?
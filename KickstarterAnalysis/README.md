# excel

**Background**

Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success.

**Project**

Modifying and analyzing the data of 4,000 past Kickstarter projects to uncover some market trends.

**Analysis**

|  | Success | Fail | Total | text |
|---- | ---- | ---- | ---- | ----|
| Total | 2,185 | 1,530 | 3,715 | overall 59% success rate
| Mean	| 194	| 18    | 113   | sucessful campaigns had a higher average number of backers 
| Median    |	62|	4   | 25 | half of all successful campaigns had more than 62 backers, while half of all failed campaigns has less than 4 backers |
| Minimum   |	1|	0| 0 | only 1 backer is necessary for a successful campaign |
| Maximum   |	26,457|	1,293| 26,457 | every failed campaign had fewer than 1,293 backers
| Variance  |	713,167|	3,776| 388,862 |  
| Standard Deviation | 844 | 61 | 624 | 

**Findings**

- Overall campaign success is associated with lower average goal amounts compared to failed campaigns. ![](Images/avg_goal.jpg)
- Overall campaign failure is associated with lower average number of backers compared to successful campaigns. ![](Images/avg_backers.jpg)

**Conclusion**
- Successful campaigns are more variable across the number of backers which makes sense because high variability indicates higher risk that may be accompanied by higher reward. It seems the failed campaigns adhere to a low variability, i.e. low risk model which leads to low reward.**



**Limitations**
- Missing demographic and marketing data.
# PyCity Schools Analysis

## Overview

A second analysis of a school district's test scores must be completed after alledged tampering of scores for the Thomas High School's ninth graders. For the analysis, NaNs ("Not a Number") replaced the math and readng grades to remove them from any district analysis. Analysis captured how the district fared by inidividual school, school size, spending per capita, and school type. The new school summaries were compared against the previous calculations. 

## Results
* *How is the district summary affected?* 
The average math and reading scores and the passing rates all decreased slightly. The overall passing rate dropped .1%, while math and reading passing percentages dropped .2% and .3% respectively. 
![Previous District Summary](./Resources/old_district_summary.png)  (Previous District Summary)
![New District Summary](./Resources/new_district_summary.png) (Recalculated District Summary)

* *How is the school summary affected?*
The only school affected by the change is Thomas High School.  While the scores are higher in the original report, there is not a significant change. 
![Previous District Summary](./Resources/old_THS_Summary.png) (Previous Thomas High School Summary)
![New District Summary](./Resources/new_THS_Summary.png) (Recalculated Thomas High School Summary)


* How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?

Thomas High School still ranks 2nd for the Overall Passing percentage. It does not affect the standings. 

![Previous District Summary](./Resources/old_district_summary.png)

* How does replacing the ninth-grade scores afect the following: The changes are so minute that the scores by school spending, school size, and school type aren't phased within the rounding format. 
	* Math and reading scores by grade: In the code, only Thomas High School's 9th grade scores were altered to NaNs. 
![School Scores](./Resources/School_summary_with_NaNs.png)
	* Scores by school spending - Thomas High School is categorized in the $630-648 range. 
![School Spending DF](./Resources/new_spending_summary.png)
	* Scores by school size - Thomas High School is categorized as Medium. 
![Scores by school size](./Resources/new_size_summary.png)
	* Scores by school type - Thomas High School is a Charter school.  
![Scores by school type](./Resources/old_type_summary.png)

## Summary
There are a few key findings from replacing the 9th grade scores
1. The amount of change in the 
2. 
3. 
4.
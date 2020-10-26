# School District Analysis
Using Anaconda to analyze standardized test scores

# Overview of the school district analysis
The school board has contacted Maria to analyze the reading and math scores of students across the district. This information will be used to plan budgets and funding allocation for the next school year. Our firm has been contacted to combine two datasets (student data and school data) to provide a clean analysis of the information. Our firm completed the analysis on the full data sets and a reduced version of the data set. The reduction eliminated the 9th grade student scores specifically from Thomas High School. The remaining data was not modified in any form. 

# Results
* How is the district summary affected?

  With a cutoff of 70% for a passing score, 75% of the students passed math and 85.8% or the students passed reading prior to removing 9th graders from Thomas High School. Once removed, the passing rates of students declined in both math and reading, with 74.8% and 85.7%, respectively. Below are images from the analysis

**Old District Analysis**
<img src="https://github.com/jratliff1215/School_District_Analysis/blob/main/School_District_Analysis/Resources/Old%20District%20Summary%202.PNG" width="1300" height="80">


**New District Analysis**
<img src="https://github.com/jratliff1215/School_District_Analysis/blob/main/School_District_Analysis/Resources/New%20District%20Summary.PNG" width="1300" height="80">


* How is the school summary affected?

  After removal of the 9th grade students, Thomas High School increased their overall passing rate from 90.5% to 90.6%, an immaterial increase in the passing rate. Both subjects of math and reading increased in passing. No other school was impacted by the removal of the students from Thomas High School. The subject school is located third from the bottom of each chart.
  
  **Original Full School Analysis**
  <img src="https://github.com/jratliff1215/School_District_Analysis/blob/main/School_District_Analysis/Resources/Old%20School%20Summary.PNG" width="2000" height="300">
  
  **Modified Full School Analysis**
  <img src="https://github.com/jratliff1215/School_District_Analysis/blob/main/School_District_Analysis/Resources/New%20School%20Summary.PNG" width="2000" height="300">
  
 
## Impact of 9th Grade Score Removal
The removal of the 461 scores for Thomas High School 9th grade has minimal impact to the overall scores and spending of the school. The scores represent only 1.2% of the total population of student scores analyzed. Spending and scores for the school and district spending is not materially impacted. Thus, our firm does not recommend the removal of the scores but rather an analysis of the noted anomalies within the data. 

# Summary
The removal of Thomas High School's reading and math scores with NaNs impacted the analysis by:

* Reduced the number of datapoints in the analysis by 461. This is only 1.2% of the total population and not statistically significant. 
* The reading score of Thomas High School was reduced by approximately 30 bps. There was no change in overall rank.
* The math score of Thomas High School was reduced by approximately 10 bps. There was no change in overall rank.
* The overall passing score decline 30 bps. This is not significant in the full analysis and had no impact the Thomas High School's overall rank. 

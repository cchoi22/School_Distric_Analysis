# School_District_Analysis
## 1. Overview
The purpose of this analysis was determine the impact of academic dishonesty from Thomas High School. Ninth graders were suspected of altering results, subsequently all scores related to ninth grade Thomas High Schoolers would be removed.

## 2. Results
### 2.1 How is the district summary affected?
In total there were 461 ninth graders that attended Thomas High School. Both reading and math scores were set to NaN and the results changed the district summary. The removal of these data points slightly decreased the overall district passing percentage from 65% down to 64.9%. Similarly boht reading and math scores dropped slightly to 74.8% and 85.7% respectively. 
### 2.2 How is the school summary affected?
The school summary changed more drastically. By removing the 461 points, both remaining reading and math scores increased from 66.911315 and 69.663609 repectively to 93.867718	and 96.539641 repectively. By removing the scores inflated the performance of Thomas High School. This moved the school's overall performance into the top 5 schools. While previously they were close to the bottom.  	
### 2.3 How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
By removing the ninth grade scores, Thomas High School moved into the 2nd highest performing school. Cabera High School remained at the number 1 spot. 

### 2.4 How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade:
    Math and reading scores for 9th graders were for Thomas High School were listed as NaN and the overall percentages of for the school changed.
- Scores by school spending:
    School spending remianed unaffected. The cacluation of the spending was not dependant on the number of students who took the reading and math scores. 
- Scores by school size:
    School size did not change due to teh score change. Only when the count of the total students scored were alterned however the size of the school remained the same. 
- Scores by school type:
    School type figures were not affected by the change.
## 3. Summary 
The removal of the ninth grade results skewed the performance positively for Thomas High School. The overall passing percentage, reading and math score percentages increased due to the removal of 461 data points. The average values were no affected due to NaN not being equal to 0 the data just didn't exist. By altering the number of students the rest of the existing data cause a increase in passing percentage. This also improved the standing of the school into the 2nd place performing school. This result should not be used as official results. Entering zeros would negatively skew the results therefore other parameters should be changed if these 461 students are removed to provide a more accurate representation of the school's performance. 

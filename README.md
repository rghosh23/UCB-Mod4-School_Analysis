# School Board Analysis with Pandas
## Overview of School District Analysis
The School Board had tasked Maria with preparing all standardized test scores for analysis, reporting and presentation in order to provide insights about performance trends and patterns. Maria has enlisted our help to complete the analysis using pandas. 
### Purpose
After completing the full analysis, it was discovered that the scores from 9th grade in Thomas High School are invalid due to reports of academic dishonesty. Maria needs our help to redo the analysis by taking out all the invalid scores and reporting on every change caused due to this instance.
## Results
- How is the district summary affected

*Analysis with invalid scores:*
<img width="1174" alt="OG-district-summary" src="https://user-images.githubusercontent.com/102441140/167346469-c8647d00-7d8b-412e-b282-ea298784ddc1.png">
*Analysis without invalid scores:*
<img width="1169" alt="New-district-summary" src="https://user-images.githubusercontent.com/102441140/167346580-56743d56-b061-4da5-9c2a-733bd52d6ec9.png">
Removing the invalid scores did not have a big impact on the district summary analysis. The average scores for math and reading remained very close and there fore the % passing math and reading and % overall passing was also very similar. Due to a large number of students from the other grades and other high schools, removing approximately 500 students did not have a huge impact on these numbers.

- How is the school summary affected

*Analysis with invalid scores:*
<img width="897" alt="OG-school-summary" src="https://user-images.githubusercontent.com/102441140/167348635-c020aa4b-c4eb-4254-b793-6ae2bdfb0bd0.png">

*Analysis without invalid scores:*
<img width="902" alt="New-school-summary" src="https://user-images.githubusercontent.com/102441140/167348731-8ced4d77-5c65-414a-9969-f9de8d236a67.png">

Removing the ninth graders reading and math scores had a drastic effect on the % passing math, % passing reading and % overall passing. After removing the invalid scores, % passing math increased from 66% to 93%. Similarly, % passing reading increased from 69% to 97% and the % overall passing increased from 65% to 90%.

- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools

In the *analysis with invalid scores:* Thomas High School ranked 8th best

In the *analysis without invalid scores:* Thomas High School ranked 2nd best

- How does replacing the ninth-grade scores affect the following:

  - Math and reading scores by grade
  
  In the new analysis, both the math and reading scores of 9th graders from Thomas High School show up as NaN
  - Scores by school spending
  
  Since Thomas High School results are in the $631-645 range, we only expect that row to be affected. We can see that the %Passing of math and reading     and % Overall passing went up as a result of removing the 9th grader data from Thomas High.
  - Scores by school size
  
  Since Thomas High School is in the Medium (1000-2000) school size range, we can expect that the medium school size row will have different results. We   can see that the same outcome as school spending occurs here. The overall % passing has improved.  
  - Scores by school type
  
  Since Thomas High School is classified as a Charter school, the charter row is the only affected row. The same trend applies here as well, % Passing of   math and reading and % overall passing went up with the omission of 9th grader data from Thomas High.
  
## Summary

By replacing the dishonest ninth grader scores from Thomas High School, we see that Thomas High School shoots up in ranking based on "% Overall Passing": from 8th best in the original analysis to 2nd best. More over, % passing in math in Thomas High School has gone up by a considerable amount, as well as % passing in reading and overall % passing. This shows that Thomas High School is really a great school because there is a drastic improvement in performance metrics following the removal of the questionable scores. 

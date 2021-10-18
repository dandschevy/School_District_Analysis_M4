# School District Analysis Module 4 Challenge

## Overview/Purpose
The purpose of Module 4 was to analyze school district data and to create multiple data frames of the resulting analysis.  The data analyzed included budget data, math and reading test scores, as well as school type and school size.  The Module 4 Challenge assignment revolved around taking the finished analysis and revising it based on information that the ninth grade math and reading scores for Thomas High School had to be removed due to academic dishonesty (cheating).  This revision required the following steps:

  1.  Replace the ninth-grade reading and math scores for Thomas High School with NaN
  2.  Repeat the entire district analysis using the revised data

Below are the results of the replacement and revised analysis.


## Results 

The number of ninth-grade students that were impacted by the adjustment to the analysis was 461; this was out of a total of 39,170 students in the entire district.  The result of the analysis are as follows
  1. District Summary: There were differences in the district summary data frame based on the removal and replacement of the ninth-grade math and reading scores.  As displayed    below, there were reductions to the average math score, % passing math, % passing reading, and % overall passing metrics. 
![District_Summary](https://user-images.githubusercontent.com/90434559/137662063-cc039f1f-169d-4f0d-9848-244004cf25ea.png)

  2. School Summary: Prior to the adjustment, Thomas High School had 83.4 average math score, 83.8 average reading score, 93.3 % passing math score, 97.3 % passing reading         score, and a 90.9 % overall passing score.  Just after the adjustment, but before the recalculation to remove the 9th grade students, the scores had dropped significantly in     the % passing math - 66.9, % passing reading - 69.7, and % overall passing - 65.1.  After the scores were recalculated to remove the ninth-grade for Thomas High School from     the total, the scores increased to % passing math - 93.2, % passing reading - 97.0, and % overall passing - 90.6.      
![School_Summary](https://user-images.githubusercontent.com/90434559/137663317-a2a020ec-e8e4-4d6e-870e-a713d89ad298.png)

  3. The adjustment had very little impact on the overall ranking compared to other schools.  Thomas High School, as diplayed above, was still number 2 in the top 5 schools.       However, the overall passing percentage decreased 0.31 points.

  4. There were minimal impacts to the spending, size or type metrics based on the change.

  5. The math and reading scores by grade were impacted as Thomas High School had no scores to calculate.


## Summary
Due to the fact the # of students impacted was 1.2% of the total population, the results were minimally impacted by the removal of the students.  The adjustment impacted Thomas High School's average math score, average reading score, % passing math score, % passing reading score, and %overall passing score.  The adjustment did not, however, impact Thomas High School's overall ranking of number 2 in the top 5.  Additionally, there was a decrease in the District's overall scores as well.  Had the number of students been greater, or more grades included, there could have been more of an impact to the District and the overall Thomas High School rankings.           


# School_District_Analysis_M4

## Overview/Purpose
The purpose of Module 4 was to analyze school district data and to create multiple data frames of the resulting analysis.  The data analyzed included budget data, math and reading test scores, as well as school type and school size.  The Module 4 Challenge assignment revolved around taking the finished analysis and revising it based on information that the ninth grade math and reading scores for Thomas High School had to be removed due to academic dishonesty (cheating).  This revision required the following steps:

  1.  Replace the ninth-grade reading and math scores for Thomas High School with NaN
  2.  Repeat the entire district analysis using the revised data

Below are the results of the replacement and revised analysis.


## Results 

The number of ninth-grade students that were impacted by the adjustment to the analysis was 461; this was out of a total of 39,170 students in the entire district.  The result of the analysis are as follows
  1. District Summary: There were differences in the district summary data frame based on the removal and replacement of the ninth-grade math and reading scores.
  As displayed below, there were reductions to the average math score, % passing math, % passing reading, and % overall passing metrics. 
![District_Summary](https://user-images.githubusercontent.com/90434559/137662063-cc039f1f-169d-4f0d-9848-244004cf25ea.png)

  2. School Summary: Prior to the adjustment, Thomas High School had 83.4 average math score, 83.8 average reading score, 93.3 % passing math score, 97.3 % passing reading         score, and a 90.9 % overall passing score.  Just after the adjustment, but before the recalculation to remove the 9th grade students, the scores had dropped significantly in     the % passing math - 66.9, % passing reading - 69.7, and % overall passing - 65.1.  After the scores were recalculated to remove the ninth-grade for Thomas High School from     the total, the scores increased to % passing math - 93.2, % passing reading - 97.0, and % overall passing - 90.6.      
![School_Summary]

### Summary
With refactoring, there are advantages and disadvantages.  In general, the advantages are a more elegant and streamlined code, less macros to run, and time savings.  The disadvantages lie in the lack of clarity or transparency of the code and issues in the ability to review the code for errors.  Additionally, another disadvantage could be the inability to revise the code easily if it has been too refactored.

For the Module 2 Challenge, the advantages of the revised code were time savings and end-user efficiency.  The disadvantage of the new code is that it would be difficult for an inexperienced coder to create it without first having created each separate macro.    


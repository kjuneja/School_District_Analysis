# School_District_Analysis

## Overview of Project

### Purpose
The purpose of this project was to submit an updated school district analysis to the school board. Th school board has found that students_complete.csv file showed evidence of academic dishonesty specially reading and math graders for Thomas High School ninth graders. The school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards. In the project we have replaced the math and reading scores for Thomas High School of Ninth Grade with NaNs while keeping the rest of the data intact. After replacing we have repeated the analysis.

This projectconsists of two technical analysis deliverables and a written report to present our results. We will submit the following:

* Deliverable 1: Replace ninth-grade reading and math scores
* Deliverable 2: Repeat the school district analysis
* Deliverable 3: A written report for the school district analysis (README.md)

### Results 

The following shows the Old Analysis with all data

![Original Analysis](https://user-images.githubusercontent.com/25447945/126091935-86050f67-13c8-4b32-b63d-d5103e43b534.png)

The following shows the New Analysis with Ninth Grade Math and Reading scores changed to NaNs for Thomas High School

![New Analysis](https://user-images.githubusercontent.com/25447945/126089921-bf9b0245-f3d8-484b-b0ca-23f15cb028f7.png)

Comparing both the Analysis we can answer the following questions:

1. How is the district summary affected?
   - We can see that much of the metrics remained the same. This was because we had a large set of data and we only removed only small portion of the data.
   
2. How is the school summary affected?
   - We can see that only Thomas High School metrics was changed and every school had the same metrics .

3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   - We can see that Thomas High School % Overall Passing decreased from 90.948012 to 90.630324

4. How does replacing the ninth-grade scores affect the following:
   * Math and reading scores by grade
     - There is no change. Metrics remained the same
   * Scores by school spending
     - There is no change. Metrics remained the same
   * Scores by school size
     - There is no change. Metrics remained the same
   * Scores by school type
     - There is no change. Metrics remained the same

### Summary 

The four major changes that occured is the number of total students, the number of students counted at Thomas High School, the average math and reading scores, the overall percentages for math and reading at Thomas High School. The data was huge and we only changed a minor data of One school, so the effect was only for one school. If we would have changed the data for all schools then there would have been a huge impact. 

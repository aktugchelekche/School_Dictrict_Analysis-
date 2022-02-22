# School District Analysis

## Overview of Project:

In this project, I will be assisting Ms. Maria who is Chief Data Scientist for a city school district and our tasked is to preparing all standardized test data for analysis, reporting and presentation to provide insights about performance trends and patterns for the district as well as each school in the district . 

#### Purpose of School District Analysis :

Main purpose of the analysis is to assist the school board and superintended in making decision regarding the school budget, improvement requirement, professional developments and other priorities.  

Upon completion of this analysis, we are tasked to discover discrepancy(ies) that occurred during 9th grade standardized testing at Thomas High School. Purpose of this task was to demonstrate the difference between summary report for district level and the school level with and without 9th grade data from Thomas High School .

*In this analysis, we will comply with full confidentiality of student personal information and FERPA ( 20 U.S.C , 1232g; 34 CFR Part 99.). Therefore, full name of a student and student ID number will not be display in any part of this report*

## Analysis

In first part of the analysis, I will remove 9th grade scores for Math and Reading from Thomas High School. Hence, we will be able two determine the differentiation between initial reports and updated report. 

Here, I utilized *Pandas* and *Numpy* dictionaries to remove those mentioned data from Thomas High School and refactor my initial code for demonstrating the following :

*The district summary.
*The school summary.
*The top 5 and bottom 5 performing schools,based on the overall passing rate.
*The average math score for each grade level from each school .
*The average reading score for each grade level from each school .
*The scores by school spending per student .
*The scores by school size. 
*The scores by school type.

## Results 

##### How is the district summary affected?
After removing 9th grade data from Thomas High School, we can observe that there is .1 to .2 decreased in **Average Math Scores, Passing Percent for Math and Reading as well as Overall Passing Percent** , there is no change in average reading scores. 

However, since we did not change the number of students, total budget for the district remained same.(School districts usually receive budget from states according to  number of students by providing snapshot on end of October.)
Initial District Summary Metric:




Updated District Summary Metric by removing Thomas High School Data:



#### How is the school summary affected?











<<<<<<< HEAD
=======
*In this analysis, we will adhere full confidentiality of student personal information and comply with FERPA ( 20 U.S.C , 1232g; 34 CFR Part 99.)*
>>>>>>> 4b96f1f56249502afe542a9b57c62bfec7efc0ad



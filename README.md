# School District Analysis

## Overview of Project:

In this project, I will be assisting Ms. Maria who is Chief Data Scientist for a city school district and our tasked is to preparing all standardized test data for analysis, reporting and presentation to provide insights about performance trends and patterns for the district as well as each school in the district . 

#### Purpose of School District Analysis :

Main purpose of the analysis is to assist the school board and superintended in making decision regarding the school budget, improvement requirement, professional developments and other priorities.  

Upon completion of this analysis, we are tasked to discover discrepancy(ies) that occurred during 9th grade standardized testing at Thomas High School. Purpose of this task was to demonstrate the difference between summary report for district level and the school level with and without 9th grade data from Thomas High School .

*In this analysis, we will comply with full confidentiality of student personal information and FERPA ( 20 U.S.C , 1232g; 34 CFR Part 99.). Therefore, full name of a student and student ID number will not be displayed in any part of this report*

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

#### How is the district summary affected?
After removing 9th grade data from Thomas High School, we can observe following cnhanges
* Average Math Score        : Decreased by 0.1%
* Average Math Score        : No Change
* Passing Percent - Math    : Decreased by 0.2%
* Passing Percent - Reading : Decreased by 0.3%
* Overall Passing Percent   : Decreased by 0.1%
* Total Budget              : No Change

Note: Since we did not change the number of students, total budget for the district remained same.(School districts usually receive budget from states according to  number of studetns they provide during snapshot window.  

Initial District Summary Metric:

  <img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155202144-27af796b-3f51-4a48-828d-253eeabc9f37.PNG">

Updated District Summary Metric by removing Thomas High School Data:

<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155201879-2b1b5d40-9df2-4783-a8db-accefed4a39f.PNG ">
            

#### How is the school summary affected?

After removing 9th grade data from Thomas High School, we can observe following cnhanges
* Average Math Score        : Decreased by 0.1%
* Average Math Score        : No Change
* Passing Percent - Math    : Decreased by 0.2%
* Passing Percent - Reading : Decreased by 0.3%
* Overall Passing Percent   : Decreased by 0.1%
* Total Budget              : No Change



<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155205186-4ed4ec43-f247-437c-aef1-f68bf5153a34.PNG">



<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155205195-903725fb-2073-4cd4-adba-42b720f3d8d3.PNG" >








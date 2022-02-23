# School District Analysis

## Overview of Project:

In this project, I will be assisting Ms. Maria who is Chief Data Scientist for a city school district and our tasked is to preparing all standardized test data for analysis, reporting and presentation to provide insights about performance trends and patterns for the district as well as each school in the district . 

#### Purpose of School District Analysis :

Main purpose of the analysis is to assist the school board and superintended in making decision regarding the school budget, improvement requirement, professional developments and other priorities.  

Upon completion of this analysis, we are tasked to discover discrepancy(ies) that occurred during 9th grade standardized testing at Thomas High School. Purpose of this task was to demonstrate the difference between summary report for district level and the school level with and without 9th grade data from Thomas High School .

*In this analysis, we will comply with full confidentiality of student personal information and FERPA ( 20 U.S.C , 1232g; 34 CFR Part 99.). Therefore, full name of a student and student ID number will not be displayed in any part of this report*

## Analysis

In first part of the analysis, I will remove 9th grade scores for Math and Reading from Thomas High School. Hence, we will be able two determine the differentiation between initial reports and updated report. 

Here, I utilized *Pandas* and *Numpy* libraries to remove those mentioned data from Thomas High School and refactor my initial code for demonstrating the following :

* Updated district summary.
* Updated the school summary.
* Updated the top 5 and bottom 5 performing schools,based on the overall passing rate.
* Updated the average math score for each grade level from each school .
* Updated the average reading score for each grade level from each school .
* Updated the scores by school spending per student .
* Updated the scores by school size. 
* Updated the scores by school type.

## Results 

#### Affects on the district summary :
After removing 9th grade data from Thomas High School, we can observe following changes:
* Average Math Score        : Decreased by 0.1%
* Average Math Score        : N/A
* Passing Percent - Math    : Decreased by 0.2%
* Passing Percent - Reading : Decreased by 0.3%
* Overall Passing Percent   : Decreased by 0.1%
* Total Budget              : N/A

Note: Since we did not change the number of students, total budget for the district remained same.(School districts usually receive budget from states according to  number of studetns they provide during snapshot window.  

Initial District Summary Metric:

  <img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155202144-27af796b-3f51-4a48-828d-253eeabc9f37.PNG">

Updated District Summary Metric by removing Thomas High School Data:

<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155201879-2b1b5d40-9df2-4783-a8db-accefed4a39f.PNG ">
            

#### Affects on  the school summary :

After calculating metrics for Thomas High School, we can observe following changes:

* Average Math Score         : Decreased by 0.06%
* Average Math Score         : Increased by 0.05%
* Passing Percent - Math     : Decreased by 27% 
* Passing Percent - Reading  : Decreased by 28%
* Overall Passing Percent    : Decreased by 26%
* Total School Budget Budget : N/A
* Per Student Budget         : N/A
* School Rank                : Dropped from second to eigth position in the district. 



<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155205186-4ed4ec43-f247-437c-aef1-f68bf5153a34.PNG">


<img width="1087" alt="Screen Shot 2022-02-22 at 6 59 27 PM" src="https://user-images.githubusercontent.com/98676400/155245457-2c7c6998-2d95-4cf8-a1fd-42e0606cc262.png">

#### Replacing the ninth-grade scores affect on the following:
* Math and reading scores by grade : There is not a significant changes in data in regard affect of replacing ninth-grade scores. 


##### Initial metrics for Math and reading scores by grade
<p align ="center">
  
<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155261092-59696417-d040-4bc4-a7ca-156d94db42cb.png">
<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155261102-f836775c-35b3-49fc-bfa4-d28c68ea975b.png" >

</p>

##### Updated metrics for Math and reading scores by grade 

<p align ="center">
  
<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155261622-8be82f1a-dbdb-43df-a71f-a62f9a6ac669.png" >
<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155261617-c875f323-ec9b-40f2-b1ae-db92701196ec.png" >

</p>

#### Chages Scores by school spending
Scores by school size
Scores by school type









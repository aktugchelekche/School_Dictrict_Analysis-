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
* Updated the average math score for each grade level from each school .
* Updated the average reading score for each grade level from each school .
* Updated the scores by school spending per student .
* Updated the scores by school size. 
* Updated the scores by school type.

## Results 

#### 1. Affects on the district summary :
After removing 9th grade data from Thomas High School, we can observe following changes:
* Average Math Score        : Decreased by 0.1%
* Average Math Score        : N/A
* Passing Percent - Math    : Decreased by 0.2%
* Passing Percent - Reading : Decreased by 0.3%
* Overall Passing Percent   : Decreased by 0.1%
* Total Budget              : N/A

Note: Since we did not change the number of students, total budget for the district remained same.(School districts usually receive budget from states according to  number of studetns they provide during snapshot window.  

Initial District Summary Metric:
<img width="943" alt="Screen Shot 2022-02-23 at 10 09 41 AM" src="https://user-images.githubusercontent.com/98676400/155359296-f7f9317e-de4b-49c1-b897-70789dae1d22.png"> 

Updated District Summary Metric by removing Thomas High School Data:           
<img width="963" alt="Screen Shot 2022-02-23 at 10 10 04 AM" src="https://user-images.githubusercontent.com/98676400/155359284-ba810a32-8e2f-40ee-b783-6b355e9a5c95.png">

#### 2.Affects on  the school summary :

After calculating metrics for Thomas High School, we can observe following changes:

* Average Math Score         : Decreased by 0.06%
* Average Reading Score      : Increased by 0.05%
* Passing Percent - Math     : Decreased by 27% 
* Passing Percent - Reading  : Decreased by 28%
* Overall Passing Percent    : Decreased by 26%
* Total School Budget Budget : N/A
* Per Student Budget         : N/A
* School Rank                : Dropped from second to eigth position in the district. 



<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155205186-4ed4ec43-f247-437c-aef1-f68bf5153a34.PNG">


<img width="1087" alt="Screen Shot 2022-02-22 at 6 59 27 PM" src="https://user-images.githubusercontent.com/98676400/155245457-2c7c6998-2d95-4cf8-a1fd-42e0606cc262.png">

#### 3. Affect on Math and reading scores by replacing the ninth grade scores are following:
* Math and reading scores by grade : There is a dropped on math & reading scores however it is not a significant changes in data in regard affect of replacing ninth-grade scores. 

Initial metrics for Math and reading scores by grade:
<p align ="center">
  
<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155261092-59696417-d040-4bc4-a7ca-156d94db42cb.png">
<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155261102-f836775c-35b3-49fc-bfa4-d28c68ea975b.png" >

</p>
                                                                                                                            
                                                                                                                               
                                                                                                                   
Updated metrics for Math and reading scores by grade:

<p align ="center">
  
<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155261622-8be82f1a-dbdb-43df-a71f-a62f9a6ac669.png" >
<img  alt="Screen Shot 2022-02-14 at 10 24 55 AM" src="https://user-images.githubusercontent.com/98676400/155261617-c875f323-ec9b-40f2-b1ae-db92701196ec.png" >

</p>

#### 4. Affect on Scores by school spending:

There is a slight/insignificant change in $630-644 range where Thomas School Distirct was placed. 
* Average Math Score         : Decreased by 0.01%
* Average Reading Score      : Increased by 0.01%
* Passing Percent - Math     : Decreased by 0.02% 
* Passing Percent - Reading  : Decreased by 0.08%
* Overall Passing Percent    : Decreased by 0.07%

Initial metrics for scores by school spending
<p align ="center">
  <img width="855" alt="Screen Shot 2022-02-23 at 9 32 29 AM" src="https://user-images.githubusercontent.com/98676400/155351831-e4a8d2f5-36f4-4ffe-9968-8624ea17ee7a.png">
</p>
Updated metrics for scores by school spending
<p align ="center">
<img width="846" alt="Screen Shot 2022-02-23 at 9 31 48 AM" src="https://user-images.githubusercontent.com/98676400/155351845-9bca2914-9110-4524-9901-ab5d52179c40.png">
</p>

#### 5. Affect on Scores by school size:
The only changes was on medium size(1000-2000 students)schools ranges where Thomas High School located in . 
* Average Math Score         : Decreased by 0.01%
* Average Reading Score      : Increased by 0.01%
* Passing Percent - Math     : Decreased by 0.01% 
* Passing Percent - Reading  : Decreased by 0.06%
* Overall Passing Percent    : Decreased by 0.07%

Initial metrics for Scores by school size:

<p align ="center">
  
<img width="788" alt="Screen Shot 2022-02-23 at 9 44 55 AM" src="https://user-images.githubusercontent.com/98676400/155354241-8a12793d-fe44-4ae3-b08d-b85ae1268323.png">
  
</p>

Updated metrics for Scores by school size:

<p align ="center">

<img width="795" alt="Screen Shot 2022-02-23 at 9 45 40 AM" src="https://user-images.githubusercontent.com/98676400/155354396-7266708d-8d0d-4ea0-9120-af4378d0bb51.png">


</p>



#### 6. Scores by school type
Since Thomas High School is one of the Charter School we are able to observe some changes in Charter School Summarry as following : 
* Average Math Score         : Decreased by 0.01%
* Average Reading Score      : Increased by 0.01%
* Passing Percent - Math     : Decreased by 0.01% 
* Passing Percent - Reading  : Decreased by 0.03%
* Overall Passing Percent    : Decreased by 0.04%

<img width="730" alt="Screen Shot 2022-02-23 at 10 00 31 AM" src="https://user-images.githubusercontent.com/98676400/155357371-7792ddae-a4f1-48c9-915f-31195eda5fe3.png">
<img width="736" alt="Screen Shot 2022-02-23 at 9 59 55 AM" src="https://user-images.githubusercontent.com/98676400/155357377-2ccca5be-2956-44b7-9871-b400e6945b68.png">

## Summary :

1. There is a significant decreased on Overall Passing Rate on School Summary as we removed 9th grade scores from Thomas High School. Therefore, Thomas HS is not competitive among charter schools. 
2. We can observe that Thomas High school is one of the Top 5 school in original data, however after removing 9th grade data, its place went down to 8th in ranking. 
3.
4. 










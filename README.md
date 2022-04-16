# School_District_Analysis.

## Overview
The school district Chiif had given us the data of 15 schools and thousands of students in those schools. We used jupter note book, panda and python to turn the data into meaningful information and make usefull insights

## Purpose 

The purpose opf the analysis was to ascertain the how the funding given to schools in the district is distributed and is ther any correlation between the amount of funding, size of school and the passing percentages of students. 
Later in the analsysis we found out that there was a issue with 9th grade students in one of the schools so we ran the analysis again and removed the whole class from the dta and then saw the same correlation and also checked if that made any differnce in the passing percentages of the student. 
 
## Resources
Data Source : School Complete .CSV & Student Complete .CSV
Python 3.8.8 , Jupyter Notebook 

## Results
We did the comparison with detailed summaries of District School before and after removing the 9th grade student's reading and math scores. Following are our findings :

### How is the district summary affected?
#### District summary before removing Thomas High School 9th Grade Students Score
![District Summary Before](https://user-images.githubusercontent.com/93050682/144174167-587e08ce-42ab-4abf-9396-d57aac254c7f.PNG)
#### District Summary after removing Thomas High School 9th Grade Students Score
![District Summary after](https://user-images.githubusercontent.com/93050682/144175952-8ef942c4-9ec8-456a-85b7-25ff064ae110.PNG)
Looking at the picture above we can see that 
* No Change in Total Students: 39,170 & Total Budget: $24,649,428.00. 
* A very slight decrese in Avg Math score
* No Change in reading scores 
* Math passing , reading passing and overall passing percentages have gone down.
### How is the school summary affected?
#### School summary before removing Thomas High School 9th Grade Students Score
![image](https://user-images.githubusercontent.com/93050682/144174871-c71baabe-40d8-4189-8126-8142d5f2eac6.png)
#### School summary after removing Thomas High School 9th Grade Students Score
![School Summary After cleaning 9th Grade](https://user-images.githubusercontent.com/93050682/144175811-68b13a1c-3f87-45a6-b86f-e7ac602e2fda.png)
The effect on school summary is not much but the the average passing scores of Thomas High school has changed, infact improved. 
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The earlier pictures show that by replacing the 9th grade score by NaN, the THS overall performance improved in comparison to other schools.
### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
There was no change in the other scores, except when we calculate as per new count and overall averag changes
#### Scores by school spending
Thomas High school falls in the spending bin of  $630-644:
* Average Math Score slighly went down
* Average Reading Score slighly went up
#### Scores by school size
The school size for Thomas High School was 1635. which falls in size medium (1000-2000):
* The average math score came down by slightly
* The average reading score went up slightly.
#### Scores by school type
The school type for Thomas High School was Charter:
* Average Math Score: 83.465425 It was 83.473852. The average math score came down by .01 points. approx.
* Average Reading Score: 83.902315 It was 83.896421. The average reading score actually went up by .01 points approx.

# Summary:
The District summary was affected as follows:
1 : Avg. Math Score came decreased
2: % Passing Math came decreased
3: % Passing Reading decreased
% Overall passing came decreased. 
Altough the differences was negligible as out of almost 40,000 students, only 461 student results were taken down. 

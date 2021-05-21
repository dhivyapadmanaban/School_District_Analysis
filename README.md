# School_District_Analysis

## Project Overview
Analyze variety of school data on student funding and student standardized test scores and provides following insights which help to make decisions regarding the school budget and priorities. After the reports of academic dishonesty on reading and math grade of Thomas High school ninth graders, those data need to be replaced with NaN's and repeat the school district analysis for the following insights. 

1. Top 5 and bottom 5 performing schools, based on the overall passing rate.
2. The average math score received by students in each grade level at each school.
3. The average reading score received by students in each grade level at each school.
4. School performance based on the budget per student.
5. School performance based on the school size.
6. School performance based on the type of school.

## Resources
- Data source : schools_complete.csv , students_complete.csv
- Software : Pandas, Jupyter notebook 

## Results
School district analysis results before and after replacing Thomas high school 9th grader scores: 

- **School District Summary**	
	- Math, Reading and overall passing percentage decreased slightly after replacing Thomas high school data for 9th graders. 

**Original Analysis**
![image](https://user-images.githubusercontent.com/83181834/119054769-12a84400-b97d-11eb-9354-d9f9c5ef3b61.png)
**Updated Analysis**
![image](https://user-images.githubusercontent.com/83181834/119054902-44b9a600-b97d-11eb-90a9-241f94e3729f.png)

- **School Summary**	
	-  There is some percentage drop in math, reading and overall passing for Thomas high school after replaced values but its less than 1 %.

**Original Analysis**
![image](https://user-images.githubusercontent.com/83181834/119064607-8bfd6200-b990-11eb-99ff-40431e826865.png)

**Updated Analysis**
![image](https://user-images.githubusercontent.com/83181834/119064639-a0d9f580-b990-11eb-9f3f-05a207dcf677.png)

- **Thomas High school performance vs  Other high schools **
	- Thomas High school performance wasn't changed and still hold second spot on top schools. 

**Original Analysis**
![image](https://user-images.githubusercontent.com/83181834/119064163-9703c280-b98f-11eb-95ca-279cf242a836.png)

**Updated Analysis**
![image](https://user-images.githubusercontent.com/83181834/119064212-b1d63700-b98f-11eb-957d-22f67d32dde4.png)


- **Following insights are affected by replacing scores.**

--> Math and reading scores by grade : Math and reading scores are affected greatly by the replacment for NaN's. As shown in below snapshot, updated analysis shows NaN's for 9th grade math and reading score for Thomas High school.
<img width="561" alt="math_score" src="https://user-images.githubusercontent.com/83181834/119066796-6de63080-b995-11eb-9495-6db4a37c9bb2.png">
<img width="588" alt="reading_score" src="https://user-images.githubusercontent.com/83181834/119066799-6faff400-b995-11eb-94d0-73408fec8148.png">

--> Scores by school spending : Percentage values dropped for spending bin $630 - 644 because of Thomas high school.
<img width="645" alt="spending_score" src="https://user-images.githubusercontent.com/83181834/119066671-23fd4a80-b995-11eb-85e8-0eb6e7b72e57.png">

--> Scores by school size : Percentage values dropped for size medium because of Thomas  high school
<img width="612" alt="size_score" src="https://user-images.githubusercontent.com/83181834/119066682-2c558580-b995-11eb-80b6-774ba6ed388c.png">

--> Scores by school type : Percentage valuse dropped for Charter school because of Thomas high school 
<img width="600" alt="type_score" src="https://user-images.githubusercontent.com/83181834/119066690-32e3fd00-b995-11eb-82aa-40f30587727e.png">


## Summary
While there is less than 1% change in data for School district summary and school summary metrics there are some big changes in other insights because of the data replacement regarding Thomas high school.
- Math and reading scores of Thomas high school 9th grade is lacking data with NaN values.
- Scores by school spending percentage values (math,reading and overall passing) dropped by 6-7% for $639-644 spending range because Thomas high school falls in that range. 
- Scores by size percentage values (math,reading and overall passing) dropped by 6% for Medium (1000-2000) range because Thomas high school student population is 1635.
- Scores by type percentage values (math,reading and overall passing dropped by 3-4% for charter schools since Thomas high school belong in that category. 


# School_District_Analysis

## Overview of Project

### Purpose
The purpose of this analysis is to show how the 9th grade reading and math scores from Thomas High School impacted Thomas High School's overall performance and how they compared to other schools. There is evidence of academic dishonesty in the math and reading scores from the 9th grade class of Thomas High School. Using pandas and the .loc function, I replaced all of the math and reading scores with NaNs. I then conducted my analysis of each schools performance. 

### Results
* How is the district summary affected?
* The district summary was not impacted heavily by removing the grades from Thomas High School's 9th grade class from the data. As you can see from the tables below, the average math score only decreased by .1, the average reading score remained constant, the passing math % decreased by .2 and the percentage passing reading decreased by .1. The overall passing percentage decreased by .3%. This does show us that the Thomas High School 9th graders did have higher scores on average than the rest of the schools, but the change was very minimal in the district summary.
        
Orginal District Summary with 9th Grade Thomas High School Data: 
![Original_District_Summary](/Resources/original_district_analysis.png) 


New District Summary without 9th Grade Thomas High School data: 
![New_District_Summary](/Resources/new_district_analysis.png)

* How is the school summary affected?
The school summary percentages are not highly affeceted by removing the 9th grade data from Thomas High School. When I removed the grades from the 9th grade class of Thomas High School, their % overall passing percentage decreased by .3%, the overall passing math percentage decreased by .1%, the overall passing reading percentage decreased by .3%. Although this is not a significant change it does show us that the 9th graders at Thomas High School were performing better on average than the other grades. 


Original School Summary with 9th Grade Thomas High School Data:
![Original_School_Summary](/Resources/original_school_summary.png)

New School Summary without 9th Grade Thomas High School Data: 
![New_School_Summary](/Resources/new_school_summary.png)

#### How does replacing the ninth-grade scores affect the following:
* Math and reading scores by grade
Since we replaced all of the 9th grade scores from Thomas High School with 0, NaN appears for the average score for Thomas High School when we pull the averages for math and reading scores based on grade.

Math Scores by Grade without 9th Grade Thomas High School Data:
![New_Math_Scores_By_Grade](/Resources/new_math_scores_by_grade.png)
Reading Scores by Grade without 9th Grade Thomas High School Data:
![New_Reading_Scores_By_Grade](/Resources/new_grading_scores_by_grade.png)

* Scores by school spending
The scores by school spending did not change when we removed the 9th grade data from Thomas High School.
* Scores by school size
The scores by school size did not change when we removed the 9th grade data from Thomas High School.
* Scores by school type


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
* The school summary percentages are highly affeceted by removing the 9th grade data from Thomas High School. Although the average reading and math scores do not change significantly, the overall passing percentages are vastly different. For instance, in my original analysis, Thomas High School had an overall passing percentage of 90.95%, but when I removed the 9th grade data, their overall passing percentage dropped to 65.07%. This shows that these scores greatly impacted their performace in comparison to other schools.

Original School Summary with 9th Grade Thomas High School Data:
![Original_School_Summary](/Resources/original_school_summary.png)

New School Summary without 9th Grade Thomas High School Data: 
![New_School_Summary](/Resources/new_school_summary.png)

* How does replacing the ninth-grade scores affect the following:
* Math and reading scores by grade
* Scores by school spending
* Scores by school size
* Scores by school type


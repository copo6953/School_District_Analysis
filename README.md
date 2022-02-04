# School_District_Analysis
## Overview
* The purpose of this project is to help Maria, the chief data scientist for the city school district, analyze data on student funding and student standardized test scores. The data was adjusted due to 9th grade scores being inaccurately reported. The analysis for this project was done using the Pandas Python library on Jupyter Notebook.
### Results
* The removal of 9th grade scores from Thomas High School decreased the district overall passing percantage by 0.1%, as shown on the district summary.
![District_Summary](https://github.com/copo6953/School_District_Analysis/blob/main/Resources/District_Summary.png)
* The removal of 9th grade scores from Thomas High School did not change any of the other schools data on the school summary, but Thomas High School's passing percentages were affected.
![School_Sum](https://github.com/copo6953/School_District_Analysis/blob/main/Resources/School_Sum.png)
* Removing the 9th grade scores from Thomas High School dramatically decreased the school's overall passing percentage from 90.95% to 90.63%.
* The math and reading scores by grade are identical other than Thomas High School 9th grade now shows NaN instead of a dishonest percentage.
* The Scores by School Spending summary, Scores by School Size summary, and Scores by School Type summary all remained unchanged after the removal of the 9th grade scores.
### Summary
Four changes to the updated analysis after replacing the 9th grade scores with NaN are:
1) The student data data frame shows NaN for every score for 9th grade students from Thomas High School.
2) The overall passing percentage of the district dropped by 0.1%.
3) The original School Summary showed Thomas High School with an overall passing percentage of 90.95%, but the updated summary shows 90.63%
4) The Scores by Grade Summary shows NaN for Thomas High School 9th grade scores.

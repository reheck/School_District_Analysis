# School_District_Analysis
## Overview of Project
### The school board is interested in the district's high schools performance in math, reading, and overall. Aside from district performance, the school board is interested in how each of the high schools compared to each other and the district as a whole regarding these scores. Furthermore, the board is interested to see how the budget per school compares with student success. Finally, the school board is interested specifically in Thomas High School and how removing 9th grade scores affects the per high school scores and the district overall scores analysis. Utilizing pandas in python, district and school summaries were created and analyzed for the school board's needs.
## Results
### > District Summary 
#### Prior to setting Thomas High School 9th grade scores to NaNs, the district summary is as follows:
![image](https://user-images.githubusercontent.com/102757676/166147286-7d9d92c5-c3a9-458f-9172-34c1cf209461.png)
#### After setting Thomas High School 9th grade scores to NaNs, the district summary is as follows:
![image](https://user-images.githubusercontent.com/102757676/166147365-bc8c0dfe-52a3-4895-ac2b-d69aadd83b47.png)
#### The percentages of students passing math, passing reading, and passing overall are reduced by a small percentage when the 9th grade scores from Thomas High School are set to NaNs yet the 9th grade students are left in the total student count. This small change in district percentages is commensurate to the the smallness of 461 9th grade students at Thomas High School compared to 39,170 students in the district.
### > School Summary
#### In contrast, Thomas High School's summary percentage values for math, reading, and overall are drastically different before and after removing the 9th grade students from high school's population.
#### For Thomas High School, the summary prior to removing the 9th graders is as follows:
Thomas High School with 9th grade NaN values
![image](https://user-images.githubusercontent.com/102757676/166164820-0c28f2ff-faca-40e0-bbae-caf79986436e.png)
#### For Thomas High School, the summary after removing the 9th graders is as follows: 
Thomas High School without 9th grade NaN values
![image](https://user-images.githubusercontent.com/102757676/166147669-7ee87262-7b47-4e65-a7de-03bdb28bf457.png)
#### Since all 461 9th grade students' reading and math scores were replaced with NaN, yet the 9th grade students were counted in the total Thomas High School population, the percentage rates for students passing math, reading, and overall falls by nearly 30%. 
#### However, when the 9th grade students are removed from the count of the total population, the passing percentages recovers to practically where it was before the 9th grade students' scores were replaced with NaNs. See the image below of Thomas High School performance before the 9th grade student's scores were replaced with NaNs.
Complete School Summary Data
![image](https://user-images.githubusercontent.com/102757676/166165867-0fde1db5-82d5-4255-bab7-42c54b9484ac.png)
### > Thomas High School Compared to Other Schools
#### If the 9th grade students are included in the total student count for Thomas High School after their scores are set to NaN, Thomas High School would appear as performing alongside the bottom 5 schools in the district. Look at the percentage overall passing rates of the bottom 5 schools in the table below and compare to the table above titled "Thomas High School with 9th grade NaN values". The bottom 5 schools have overall passing rates in the 50% range and Thomas High School has an overall passing rate of 65%. 
Bottom Five Performing Schools (No Thomas HS 9th graders)
![image](https://user-images.githubusercontent.com/102757676/166166275-3df37d4c-85dc-4e91-bbc6-87860db8287b.png)
#### However, removing the 9th grade student data keeps Thomas High School in the top 5 performing high schools, maintaining its rank as second top performing. Refer to the top 5 schools without the Thomas High School 9th graders in the table below.
Top Five Performing Schools (No Thomas HS 9th graders)
![image](https://user-images.githubusercontent.com/102757676/166166289-2d37b3c8-860e-4638-9372-1c8a7bf6df2e.png)
### > Other Effects of Replacing the 9th Grade Scores for Thomas High School
#### The math and reading scores show NaN values for 9th graders when the 9th grade scores are replaced. Refer to the Math table shown below.
![image](https://user-images.githubusercontent.com/102757676/166166496-1475af0c-bc7d-4b58-a550-b8b486454d14.png)
#### Scores by school spending are not affected by replacing the 9th grade scores, and neither are the scores by school size or scores by school type. 
## Summary
### To conclude, when reading and math scores are replaced with NaNs for the 9th grade students at Thomas High School, there are 4 changes to the school district analysis. The four changes are 1) the percentage of students in the entire district that are passing math, reading, and overall is reduced by a small percentage, 2) the percentage of students passing math, reading, and overall at Thomas High School is severely reduced, 3) the performance ranking of Thomas High School compared to the other schools in the district drops into the lower half with the poorer performing schools, and 4) Thomas High School's average math and reading scores for 9th graders is unavailable for comarison with the other school's 9th graders.

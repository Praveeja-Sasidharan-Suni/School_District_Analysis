# School District Analysis

## Project Overview
### The purpose of this project is to analyze the data of an entire School District based on some subjects such as Maths and Reading, funding,school types and student grades.The file 
shows evidence of academic dishonesty in reading and math grades for Thomas High School ninth graders.So we need to replace the math and reading scores for Thomas High School with NaNs
while keeping the rest of the data intact. Once we have replaced the math and reading scores,we have to repeat the school district analysis and write up a report to describe
how these changes affected the overall analysis.

## Resources
**Resources:** All data used in this analysis is found inside (https://github.com/Praveeja-Sasidharan-Suni/School_District_Analysis/tree/main/Resources) folder.

**Software:** Python 3.7, Anaconda, Jupyter Notebook

## Results
### Deliverable 1
Due to potential academic dishonesty by the ninth grade students of Thomas High School, this analysis was conducted twice. The first trial of this analysis included the full set of student
 data.In the second trial of this analysis, the ninth grade students of Thomas High School had their scores omitted from the calculations. The entire ninth grade class of Thomas High School have
 had their scores replaced with NaN. 

![deliverable1](https://github.com/Praveeja-Sasidharan-Suni/School_District_Analysis/blob/main/Images/deliverable1.PNG?raw=true)

### Deliverable 2
1. *The School summary after replacing the ninth graders' scores with NaNs.*
![updated_school_summary](https://github.com/Praveeja-Sasidharan-Suni/School_District_Analysis/blob/main/Images/updated_school_summary.PNG?raw=true)

2.*The District summary after replacing the ninth graders' scores with NaNs.*
![updated_dist_summary](https://github.com/Praveeja-Sasidharan-Suni/School_District_Analysis/blob/main/Images/updated_dist_summary.PNG?raw=true)

- Replacing the ninth graders' math and reading scores with NaN resulted in the following changes for Thomas High School:
  - The overall passing percentage for Thomas High School fell to 65%
  - The overall passing percentage for the entire district fell to 64.9%
  

- When the ninth graders' of Thomas High School had their scores omitted from the calculations, the following changes occured:
  - The overall passing percentages of Thomas High School decreased by 0.11%
  - The average scores of Thomas High School for math and reading *increased* by 0.06
  - For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%
  - **School rankings are unchanged.** Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.
3.*The top 5 performing schools, based on the overall passing rate*

![top_five_schools](https://github.com/Praveeja-Sasidharan-Suni/School_District_Analysis/blob/main/Images/top_five_schools.PNG?raw=true)

4.*The bottom 5 performing schools, based on the overall passing rate*

![bottom_five_schools](https://github.com/Praveeja-Sasidharan-Suni/School_District_Analysis/blob/main/Images/bottom_five_schools.PNG?raw=true)

5.*The average math score for each grade level from each school* 


![math_grade_level](https://github.com/Praveeja-Sasidharan-Suni/School_District_Analysis/blob/main/Images/math_grade_level.PNG?raw=true)

6.*The average reading score for each grade level from each school*

![reading_grade_level](https://github.com/Praveeja-Sasidharan-Suni/School_District_Analysis/blob/main/Images/reading_grade_level.PNG?raw=true)

##### Average Scores by Grade Level
After analyzing the average scores for math and reading by grade levels for each school, it is found that a students grade level does not affect their scores as much as the school that they
 attend. The average scores within each school only varries by 1-2% depending on grade level. However, the difference in scores is more apparent when comparing different schools. 


7.*The scores by school spending per student* 

##### The Effects of School Budget and School Size

It is found that Average Scores and Passing Percentages do not increase as spending per student increases. In fact, the top performing school in the entire school district 
(Cabera High School) received $68 *less* per student than the lowest performing school (Johnson High School). This implies that there are more relevant factors than funding 
that decide average student scores.

![scores_by_schools_spending](https://github.com/Praveeja-Sasidharan-Suni/School_District_Analysis/blob/main/Images/scores_by_schools_spending.PNG?raw=true)


8. *The scores by school size*

When considering School Sizes, "Large" Schools (Over 2,000 Students) have the lowest average scores and passing percentages. The difference in performance between "Small" and "Medium" Size
Schools is negligible (approximately 1%). Interestingly, all District schools in this dataset are characterized as "Large" schools. This may be an indication that students in this district
learn and perform better in smaller, more intimate settings.

 
![scores_by_school_size](https://github.com/Praveeja-Sasidharan-Suni/School_District_Analysis/blob/main/Images/scores_by_school_size.PNG?raw=true)

9. *The scores by school type*

#### Charter vs. District Schools
Charter schools generally performed better than District schools in this analysis. The top five schools with the highest overall passing percentages are all Charter schools, 
whereas the bottom five are all District Schools. Charter schools in this dataset were typically characterized as "Small" and "Medium" size schools. 
As seen in the DataFrame below, **Charter schools have a 36% higher overall passing percentage** than District schools.

![scores_by_school_type](https://github.com/Praveeja-Sasidharan-Suni/School_District_Analysis/blob/main/Images/scores_by_school_type.PNG?raw=true)

## Summary

Unfortunately, it is not possible to determine the extent of the potential academic dishonesty or identify specific indivuals to exclude from the dataset. As a consequence of this,
the entire ninth grade of students from Thomas High School have had their scores omitted from the results. This is a suboptimal situation because a full set of data is ideal for
creating the most accurate results.

Replacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to come down a little. 
The district as a whole has also had its average math and reading scores decrease, as well as the overall passing percentage for students. However, after updating the total student counts 
to exclude the Thomas High School ninth graders and omitting their scores from the dataset,Thomas High School regained its high average scores and retained its position as the number two
 school in the District.



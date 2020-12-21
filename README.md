# School_District_Analysis

## Overview of the School District Analysis 
The school board has requested for help due to the students_complete.csv file showing evidence of academic dishonesty; specifically for subjects reading and math for Thomas High School appear to have been changed. Maria has asked to replace the math and reading scores for Thomas High School with NaNs while keeping the remainder of the data intact. Once the math and reading scores have been replaced, we were to repeat the school district analysis that was done in the module. This challenge consisted of two techincal analysis deliverables using Pandas/Jupyter notebook. Jupyter notebook is a useful and important tool to use during analysis as it allows us to create and share documents that contain live code, visualizations and text. 

## Results 
**How is the district summary affected?**</br>
The district summary consists of 15 schools with a total of 39,170 students. The columns within the dataframe are Total Budget, Average Math Score, Average Reading Score, 
% Passing Math, % Passing Reading, and the Overall passing percentage. When comparing the district summary between the original code in the module and the challenge, 
there was not a significant difference shown. The average math score calculated to 78.9 with a passing percentage of 74.8%, while the average reading score calculated to 81.9
with a passing percentage of 85.7%. The overall passing percentage was 64.9%. The results indicate that students score higher in reading compared to math. 

District summary:</br>
![challenge_district_summary](https://github.com/echuung94/School_District_Analysis/blob/main/Resources/challenge%20district%20summary.png)
Original summary:
![original_district_summary](https://github.com/echuung94/School_District_Analysis/blob/main/Resources/original%20district%20summary.png)

**How is the school summary affected?**</br>
Based on the findings below, out of the 15 schools, there are 7 schools are District and 8 schools that are found in the Charter level. The range of students were found between
Holden High School with a total of 427 students and Bailey High School with a total of 4976 stduents. The findings also showed that although there are more schools in the charter 
level, there are more students within the district level.

School summary: 
![school_summary](https://github.com/echuung94/School_District_Analysis/blob/main/Resources/school%20summary.png)

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**</br>
In the original school summary, Thomas High School was not the lowest perfoming school, but they have a low percentage performance rate compared to the other charter level
schools. Their Overall passing percentage was a 65%. Replacing the ninth grader's math and reading scores affected their overall performance to be reported consistent with 
the other schools in the charter level. The passing math percentage was a 93% and the passing reading percentage was a 97% with a overall passing percentage of 90.6%. 

Summary with Replaced 9th graders' Math and Reading Scores
![replaced_school_summary](https://github.com/echuung94/School_District_Analysis/blob/main/Resources/replaced%20school%20summary%20.png)

**How does replacing the ninth-grade scores affect the following:**</br>
- Math and reading scores by grade
In the findings below, replacing the ninth-grade score affects the results for Thomas High School. The value originally reported for math was 83.6, the reaplacement data
has changed that value to show NaN. The value reported for reading before the value was replaced was 83.7, now it is shown as NaN. Replacing the ninth grade scores with NaN did
not seem to affect the overall math and reading scores by grade significantly. 

Math Scores by Grade:
![math_scores_by_grade](https://github.com/echuung94/School_District_Analysis/blob/main/Resources/math%20scores%20by%20grade.png)</br>
Reading Scores by Grade:
![reading_scores_by_grade](https://github.com/echuung94/School_District_Analysis/blob/main/Resources/reading%20scores%20by%20grade.png)

- Scores by school spending</br>
The total budget dataframe showed the amount of money each school consumed. The maximum amount consumed was by Bailey High School with #3,124,928.00 and the least amount consumed was by Holden High School with $248,087.00. The results also show that the Huang High School has the highest amount per student budget at $655. Although they charge students the highest, we also see that they are not included in the top five performing school.

School Spending: 
![school_spending](https://github.com/echuung94/School_District_Analysis/blob/main/Resources/school%20spending.png)

Top Performing Schools:
![top_performing_schools](https://github.com/echuung94/School_District_Analysis/blob/main/Resources/top%20performing%20schools.png)

- Scores by school size
According to the findings, the medium school size (1000-2000) had the highest overall passing rate of 90.6%. While reviewing the entire summary of the schools, Cabrera High School showed the highest overall passing rate amongst the other medium school size, with a passing rate of 91.3%. Going over the large school size data, the overall passing percentage was reported to be 58.2%. Wilson High School had the highest overall percent with 90.6%. The other schools within the large frame, reported around 50%.

School Size:</br>
![school_size](https://github.com/echuung94/School_District_Analysis/blob/main/Resources/school%20size.png)

Size Summary:</br>
![size_summary](https://github.com/echuung94/School_District_Analysis/blob/main/Resources/size%20summary.png)

- Scores by school type:</br>
In the summary below, the schools in the charter level had a higher overall passing percentage compared to the district level. The charter had an overall passing percentage of
90% while the district level reported a 54%. The average scores for math and reading were reported higher by the charter level as well. The charter average math score reported a 83.5% while the district average math score 77%. For average reading, charter reported a 83.9% while district reported 81%. 

School Type:</br>
![school_type](https://github.com/echuung94/School_District_Analysis/blob/main/Resources/school%20type.png)

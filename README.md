# School District Analysis

## Overview of Analysis

In this analysis, we are working with Maria, a data scientist for a city school district. We will be preparing 
standardized test data for analysis and reporting. The aggregated data will then be presented to the city school
board and superindentent in an effort to provide insights regarding school funding and student test scores. The
board and superindendent with then use the analysis to help inform their strategic decisions regarding the
school budget.

### Purpose

The purpose of this project will be to update our Python code to account for reports of academic dishonesty
and alterations made to student test scores. In this new analysis, we will be working to update the data, to
repeat the school district analysis and lastly describe how the changes made impacted the overall analysis. 

## School Analysis Results

Following the updates to the test score data, various aspects of the previous analysis have been affected. 

- Distrct Summary

As seen in the images below, the Totat Schools, Students and Budgets fields, have not been impacted. However, the Average Math Scores, % Passing Math,
% Passing Reading and % Overall Passing have been lowered. However, the changes on these calculations have been minimal, with the largest change being
a .3% drop to the %Passing Reading.

Original
![This is an image](https://github.com/jstawarz/School_District_Analysis/blob/main/Resources/District_Analysis_Original.png)

Updated
![This is an image](https://github.com/jstawarz/School_District_Analysis/blob/main/Resources/District_Analysis_Updated.png)

- School Summary

Overall, the School Summary is minimally impacted. Since the changes in test scores were isolated to Thomas High School, the data points
for the other high schools were not impacted. However, the data for Thomas High School itself was affected. The Average Math, % Passing Math
% Passing Reading and the % Overall Passing all decreased when the 9th grade results were removed. Conversely, the Average Reading increased
when the scores were removed. 

Original
![This is an image](https://github.com/jstawarz/School_District_Analysis/blob/main/Resources/Thomas_High_School_Original.png)

Updated
![This is an image](https://github.com/jstawarz/School_District_Analysis/blob/main/Resources/Thomas_High_School_Updated.png)

- Thomas High School Relative to Other Schools 

In comparison to other schools, the change to the test scores did not ultimately impact Thomas High Schools ranking. It is still the 2nd
highest ranked school with 90.63% of its students passing both the math and reading standardized tests.

![This is an image](https://github.com/jstawarz/School_District_Analysis/blob/main/Resources/Top_Schools.png)

In addition, removal of the 9th graders test scores also affects subsequent analyses. 

- Math and Reading Scores by Grade

Of course when looking at the scores by grade level, removal of Thomas High Schools 9th grade scores results in NaN displayed as the 9th
grade result for Thomas High School. No other schools are impacted by this change. 

Original
![This is an image](https://github.com/jstawarz/School_District_Analysis/blob/main/Resources/Math_scores_%20bygrade.png)

Updated
![This is an image](https://github.com/jstawarz/School_District_Analysis/blob/main/Resources/Reading_scores_bygrade.png)

- Scores by School Spending

With a Per Student Budget of $638, the removal of Thomas High Schools test scores will only impact the $630 to $644 spending range. Here, 
the Average Math Score, % Passing Math, % Passing Reading and % Overall Passing all decrease with the updated data. While, Average Reading Score 
increased for the $630 to $644 range. 

Original
![This is an image](https://github.com/jstawarz/School_District_Analysis/blob/main/Resources/School_Spending_Original.png)

Updated
![This is an image](https://github.com/jstawarz/School_District_Analysis/blob/main/Resources/School_Spending_Updated.png)

- Scores by School Size

As a medium size school, the changes impact the data reports for medium schools in a similar way as the school spending report. Again, the 
the Average Math Score, % Passing Math, % Passing Reading and % Overall Passing were all lowered with the new reports. Similarly, the Average
Reading score increased.

Original
![This is an image](https://github.com/jstawarz/School_District_Analysis/blob/main/Resources/School_Size_Original.png)

Updated
![This is an image](https://github.com/jstawarz/School_District_Analysis/blob/main/Resources/School_Size_Updated.png)

- Scores by School Type

Lastly, as a charter school, the changes to the test score data again lower the Average Math Score, % Passing Math, 
% Passing Reading and % Overall Passing scores for the Charter schools as a whole. 

Original
![This is an image](https://github.com/jstawarz/School_District_Analysis/blob/main/Resources/School_Type_original.png)

Updated
![This is an image](https://github.com/jstawarz/School_District_Analysis/blob/main/Resources/School_Type_Updated.png)

## School Analysis Summary

In sum, the updates made to reading and math scores at Thomas High school resulted in significant
changes in the analsyis results.

First, in the district summary, we see an overall decrease in the average math and reading scores, as well as a drop in the percentage of students
that passed math, reading and both tests. This would suggest that overall, the 9th grade scores from Thomas high school were slightly higher than
the previous average and would reflect that a number of students passed their exams. However, they do not appear to have been a statistical outlier
that was having any outsized impact on the district as a whole. 

A second example of these changes can be seen in Thomas High Schools overall test results. The removal of the scores is an overall negative to the
schools score results as the Average Math, % Passing Math, % Passing Reading and the % Overall Passing all decreased.

A third instance is seen in the School spending reports. Similarly to the impacts of the change seen to Thomas High Schools scores, the removal of the
ninth grade test scores lowers the Average Math, % Passing Math, % Passing Reading and the % Overall Passing for the $630 to $644 spending range. 

Finally, as a medium sized charter school, the change in test scores affects the statistics for these summaries. In both cases, the
Average Math Score, % Passing Math, % Passing Reading and % Overall Passing fields are all lower than previously reported.



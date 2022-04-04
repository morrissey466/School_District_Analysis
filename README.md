# School District Analysis

## Overview 
This analysis looks into data from several different high schools to determine what factors might play a role in overall student performance. Student grades from several school districts and facts about those schools are used in this analysis. We breakdown passing reading and math scores from several schools, and compare them to the size of the school and the per capita budget to determine if they have an effect on passing rates. 

## Results 

This report compares the challenge results from the results of the module. The challenge results have omitted the freshman class from Thomas High School while the module contains a complete set. 


DISTRICT SUMMARY 

- The district summary is the same as the module because we did not use the "new_student_count" variable as per instructions in the challenge. The module rounded to different decimal rounding on this summary, but numbers are unchanged as the replacing of Thomas High School's freshman grades since the dataset is so large. 

- On the Per School Summary Table, removing freshman grades decreased the overall passing scores signifgantly since NaN did not count as a passing score and the student count was not updated for the table. The table would be better if the number of students equaled the total number minus the freshman students. 


- Replacing the math and reading scores for Thomas High School's freshman minimally effects their average reading and math scores, but it greatly decreases their passing rates because the freshman class's grades were omitted from the data. The analysis should have accounted for this and omitted the freshman from the total student count when calculating passing rates. 

- Math and reading scores by grade for Thomas High School were not affected except for the fact that there is not a metric for the freshman class. 

- Scores by school spending decreased slightly in the $631-645 category because of the omitted freshman data 

- Scores by school size were not significantly effected by the omitting of the Thomas High School Freshman data. 

- Scores by school type were not significantly effected by the omitting of Thomas High School freshman data. 

## Summary 

Overall, the omitting of data for Thomas High School freshman had a small effect on averages of the whole data set. When we look at the data specifically for Thomas High School, there is a large decrease in the passing rates. This has to do with the table not reducing the student count when calculating passing percentages. The scores by school type and scores by school size were minimally effected because they used and average of all the data, and the data set was large so omitting partial data from one school did not have much of an effect. The average math and reading scores for Thomas High School was not much effected due to the null values not being counted as zeros, and the small discrepancy with pass rates by grade for math and reading scores. 
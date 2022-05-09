# School_District_Analysis

Overview of the school district analysis: Explain the purpose of this analysis.

Prepare and analyze all standardized test data from a school district for analysis, reporting and presentation to provide insights about performance trends and patterns.
These insights are to inform discussions and strategic decisions at the school and district level. 

Analyze data on student funding and student's standardized test scores (Math and reading) and various information on school's they attend
Task: Aggregate the data and showcase trends in school performance. This will assist the school board and superintendent in making decisions regarding the school budgets
and priorities. While working on this task, we'll need to mantain the data confidential as part of the Family Educational Rights and Privacy Act (FERPA) of 1974 which
protects the privacy of student education records. 
Additionally the school district provided that the standardized test scores for ninth grade students at Thomas High School were incorrect, and they requested for updated data summaries.

After analyzing the data, it was best to only replace the ninth grade math and reading scores at Thomas High School instead of removing them because this will provide the best accuracy while keeping all other data associated with this student group intact.

The Math and Reading scores were replaced with "NaN", which means a "Not-a-Number" value resulting in a closer representation of the original data.

Results: Using bulleted lists and images of DataFrames as support, address the following questions.

## District Summary
The average math score and passing percentages and the overall passing percentage among the 15 high schools in the school district changed, the average math score dropped 1.9%, the average reading score stayed the same, the percentage passing math dropped 1.8%, the percentage passing reading dropped 1.7%, and the overall passing percent dropped 1.9%.

New
![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/New%20district%20summary.png)

Original
![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/original%20district%20summary.png)


## School Summary

When assessing school summaries and performing schools, the score replacements did not affect the ranking of the top five performing schools. Thomas High School ranked second place in the top five performing schools with a 90.95% overall passing. After replacing both math and reading scores, Thomas High School was still among the top five with the overall passing unchanged. On the plus side, these changes did not place Thomas High School among the bottom five performing schools. Those ranks remained the same. Per the revised School Summary, Thomas High School now ranks 13th place among 15 high schools in the district just as it did in the original analysis.

New Top 5 School
![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/new%20top%205%20schools.png)

Original Top 5 School
![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/Original%20top%205%20schools.png)

## The ninth graders’ math and reading scores from Thomas High School.
Another plus side from this data replacement is that it did not change the math and reading scores. Given, both the average math and reading score summaries were stratisfied by school and grade level. As shown above, the summary tables display "NaN" for ninth grade at Thomas High School whereas the remaining data remained intact.

New Math Thomas High School 9th grade scores

![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/new%20math%20scores.png)


New Reading Thomas High School 9th grade scores

![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/new%20reading%20scores.png)



Original Math Thomas High School 9th grade scores

![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/original%20Math%20scores.png)


Original Reading Thomas High School 9th grade scores

![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/original%20Reading%20scores.png)


## Scores by school spending
When reviewing the School Spending summary, this data change did not impact the spending ranges for either the average math scores or average reading scores for the first spending group (<$586) and the last spending group ($646-$675). The second spending group ($586-$630) did show a shift of the Average Math Score by 1.7%, the average reading score by 0.7%, the passing Math percentage increasead by 7%, the passing reading percentage increased by 3%, and the overal passing increased by 9%. 
The spending group ($631-$645) also show a positive shift or increase of all the different categories such as the Average Math Score by 0.6%, the average reading score by 0.3%, the passing Math percentage increasead by 3%, the passing reading percentage increased by 2%, and the overal passing increased by 3%.


New School Spending
![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/new%20school%20spending.png)

Original School Spending
![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/original%20school%20spending.png)


## Scores by school size
When reviewing the School Size summary, removing the ninth grade scores did not affect any of the categories at all. This is probably because we are dealing with an enormous student size and removing the school grade of one single school doesn't affect the overall results when we filtered by school size. 


New School Size
![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/new%20school%20size.png)

Original School Size
![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/original%20school%20size%20.png)

## Scores by school type
In reviewing the last summary on School Types, this data change did not affect the passing percentages that compared charter and district schools as well as the average scores for these two school types. Removing the scores did not impact this category.

New School Type
![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/new%20school%20type.png)

Original School Type
![](https://github.com/nadiezhdamhb/School_District_Analysis/blob/main/Original%20School%20Type.png)

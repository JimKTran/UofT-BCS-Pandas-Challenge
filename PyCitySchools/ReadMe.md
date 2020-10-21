# PyCitySchools Pandas Homework
## _Due: Oct. 24, 2020_
### _Submitted By: Jim Tran_

![education](Images/education.png)

*The main objective of the PyCitySchools homework assignment is to develop pandas scripts to analyze the schools and students datasets, given 2 raw data files in csv format; 'school_complete.csv' and 'students_complete.csv'.  The schools data is describe with a unique school ID, 14 school_name categorized as either district or charter types; and columns for the school size and their budgets.  With columns of data from student IDs, student_name, gender, grade, school_name, reading_score and math_score; the students data can be merged with the schools data by the school_name field.  Althouth, the 2 datasets were imerged and was initally used to calculate the total_schools by using the len(unique) function, but the dataset was ultimately not necessary as it was easier to separately use the schools and students datasets to calculate require metrics/data series ie. count of school_name for total_schools metric.  A view of datasets:*
[raw datasets](Images/schools_students.png)

*Various metrics are calculated to produce different summary datasets for analysis; such as [district summary](Images/district_summary.png) dataframe where the total view of overall district school and student  metrics are presented.  This include:*
  * Total Schools 
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score 
  * Percentage of Passing Math 
  * Percentage of Passing Reading
  * Percentage of Overall Passing 

*Next, is a drill down of the same metrics for each school is summarized in the [school summary](Images/school_summary.png).  Other data summaries include:*
  * Top 5 Performing Schools by Overall Percentage
  * Bottom 5 Performing Schools by Overall Percentage 
  * Math Scores per Grade by Schools 
  * Reading Scores per Grade by Schools 
  * Scores by School Spending
  * Scores by School Size
  * Scores by School Types

*One of the interesting summary to look at is the [top 5 performing schools](Images/top_performing.png) and the [bottom 5 performing schools](Images/bottom_performing.png) summary.  The top 5 schools are from charter types where there are less students per school with less total budget and less per student budget.  And the bottom 5 are from district types with more students per school, higher total budget and higher per student budget.  In fact, the [Scores by School Spending](Images/scores_by_spending.png) summary show that less per student budget have higher passing percentage.  The [scores by school sizes](Images/scores_by_size.png) summary also show smaller schools sizes and the [scores by school types](Images/scores_by_types.png) summary show charter school types have higher overall passing percentage.The differenes may be due to smaller class size with smaller student to teacher ratio for more direct learning.  However, this assumption is only based on the given data and more data about students to techers ratio would be needed to make this conclusion.*

This analyis was built using this [code](PyCitySchools/PyCitySchools.ipynb)

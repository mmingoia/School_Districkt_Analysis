# School_District_Analysis

UTDA - Module 04 -

## Deliverables for the Analysis - Lesson

1. A high-level snapshot of the district's key metrics, presented in a table format
2. An overview of the key metrics for each school, presented in a table format
3. Tables presenting each of the following metrics
   1. Top 5 and bottom 5 performing schools, based on the overall passing rate
   2. The average math score received by students in each grade level at each school
   3. The average reading score received by students in each grade level at each school
   4. School performance based on the budget per student
   5. School performance based on the school size
   6. School performance based on the type of school

## Challenge

1. Recreate the district and school summary DataFrames.
   1. How is the district summary affected? The district summary has minor changes to the Average math and reading scores, the average math score changed from 79.0 to 78.9 and the average reading score stayed the same at 81.9.  However the passing percentage changed more significantly.  Math decreased from 75% to 74% and reading changed from 86% to 85%.  Overall reduced from 65% to 64%.  The small change in the average is because the scores that were removed were completely eliminated from the averages.  The passing rate was affected more because the removed scores counted as not passing so they had a larger impact.  This is a consistent theme throughout the updated tables.  Average scores had small changes, but passing rates had a more noticeable change.
   2. How is the school summary affected? The only school affected in the school summary is Thomas High School. It had its average math and reading scores were essentially the same and stayed at 83.4 and 83.9 respectively. They did change in past the tenths place. It's passing math dropped from 93.3 to 66.9, it' passing reading dropped from 97.3 to 69.7 and its overall passing dropped from 90.9 to 65.1.
2. Recalculate the high- and low-performing schools.
   1. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools? Prior to replacing the scores, Thomas was the ranked second based on overall passing %.  It has dropped out of the top five and is at number eight.  The bottom five is unaffected by this change.
3. Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type.
   1. How does replacing the ninth-grade scores affect the following?
      1. Math and Reading Scores by Grade - The only change in the tables for Math and reading are the 9th grade scores for Thomas has been replaced by "nan"
      2. Scores by School Spending - The only change in the table is in the "$630-644" range. The average scores are unchanged when rounded to the tenths place, but the passing rates have dropped.  Math from 73% to 67%, reading from 84% to 77% and overall from 63% to 56%.
      3. Scores by School Size - The only change in the table is in the "Medium" range. The average scores are unchanged when rounded to the tenths place, but the passing rates have dropped.  Math from 94% to 88%, reading from 97% to 91% and overall from 91% to 85%.
      4. Scores by School Type - The only change in the table is in the "Charter" range. The average scores are unchanged when rounded to the tenths place, but the passing rates have dropped.  Math from 94% to 90%, reading from 97% to 93% and overall from 90% to 87%.

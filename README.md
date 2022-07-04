# School_District_Analysis

## Project overview
Maria, a data scientist for the school district, regularly compiles standardized math and reading scores and aggregates multiple datasets to help determine school performance on multiple levels, as well as how school funding may affect test scores.  Upon an internal audit, it was discovered that there was academic dishonesty and score manipulation with the 9th grade class at Thomas High School.  The school board is looking for an updated analysis, excluding the test scores from the 9th grade class at THS.

1. The Reading and Math scores from the THS 9th grade class should be removed from the dataset and the analysis.
2. The overall school district analysis should be recreated, excluding the data from the THS 9th grade class.

## Resources
- Data Sources: schools_complete.csv; students_complete.csv
- Software: Anaconda Prompt 4.13.0; Jupyter Notebook


## Results
Additional analysis of the data shows:

1. **District Summary:** There were slight drops in Average Math Score and Passing Percentages.  Average Reading Score was mostly unaffected.

2. **School Summary:** Other schools were not affected, but Thomas High Schools shows drops in Average Math Score and Passing Percentages.  Average Reading Score went up slightly.

3. **Top Schools Ranking:** Overall rankings did not change, but again, THS showed drops in Average Math Score and Passing Percentages.  Again, Average Reading Score went up slightly.

4. **Math and Reading Scores by Grade:** Other grades were not affected.  9th grade scores for THS were removed.

5. **Spending Ranges:** Spending Ranges per student were largely unaffected.

6. **School Size:** Average Scores and Passing Percentages were largely unaffected.

7/ **School Type:** Average Scores and Passing Percentages were largely unaffected.


## Summary
Removing the scores from the 9th grade class at Thomas High School only marginally changed their scores and did not affect their overall ranking in the school district.  As noted, their Average Math Score, Passing Math percentage, Passing Reading percentage, and Overall percentage went down slightly.  Average Reading Scores were not affected in the overall district and actually improved at THS.  With this information, if there was academic dishonesty with the 9th grade class at THS, it is likely it resulted from isolated incidents from within the class and not systemic of the entire grade.
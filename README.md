## Summary

With almost 40,000 students within the district, I looked at the district-wide standard test results (found in the [students_complete.csv](data/student_complete.csv)) among  15 schools, with their data found in [schools_complete.csv](data/schools_complete.csv)). My goal is to use Pandas to aggregate the data in order to showcase trends in school performance. 

## Scope

Before performing any aggregations for analysis, both datasets had to be loaded in using Pandas, and stored as Pandas Dataframes. Then the next step was to combine both dataframes into one dataframe to be able to include school information with the student information.
![Combined Data](images/combined.png)

I created Python scripts in order to manipulate the original dataframe to create new dataframes that show us:
 - District Summary

 ![District Summary](PyCitySchools/images/district_summary.png)

 - School Summary

 ![School Summary](PyCitySchools/images/school_summary.png)

 - Scores by School Spending

 ![By Spending](PyCitySchools/images/spending.png)

 - Scores by School Type
 
 ![By Type](PyCitySchools/images/type.png)

 - Scores by School Size
 ![By Size](PyCitySchools/images/size.png)

 - Top and Bottom Performing Schools
 - Math and Reading Scores by Grade

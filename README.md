# School_District_Analysis
## Background

### School District Analysis Overview
This project utilized python/pandas in jupyter notebook to analyze a city's school district data. The purpose of running these analyses was to help the school board/mayor make strategic decisions regarding the school's future budgets/priorities.

Two files in .csv format (school_complete.csv; students_complete.csv) were provided as starting points for this project. The school_complete.csv file contains data in the following columns: Student ID, school_name, type, size, and budget. The students_complete.csv file contains data in the following columns: Student ID, student_name, gender, grade, school_name, reading_score, and math_score. Data from both files was imported, manipulated, and then aggregated into python/pandas dataframes for accessible viewing/analysis.

### Challenge Overview
This challenge encompassed re-completing the analysis due to the school board being notified that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. I re-completed the analysis from Module 4 after taking the academic dishonesty of the Thomas High school ninth graders into account by removing their math and reading scores from the data.

The final file with the code to alter the data for this challenge is: PyCitySchools_Challenge.ipynb.

## Results
The district summary was only slightly affected after the challenge (small drops in all variables): see the following images -

**Old District Summary**
![Old District Summary](https://github.com/marikachrisanthopoulos/School_District_Analysis/blob/main/Resources/District_Summary_Old.png)

**New District Summary**
![New District Summary](https://github.com/marikachrisanthopoulos/School_District_Analysis/blob/main/Resources/District_Summary_New.png)



The school summary was affected: Math, Reading, and Overall Scores for Thomas High School were altered significantly (significant drop after re-analyzing the data for the challenge): see the following images -

**Old School Summary**
![Old School Summary](https://github.com/marikachrisanthopoulos/School_District_Analysis/blob/main/Resources/School_Summary_Old.png)

**New School Summary**
![New School Summary](https://github.com/marikachrisanthopoulos/School_District_Analysis/blob/main/Resources/School_Summary_New.png)



**Old Scores by School Spending**
![Old Scores by School Spending](https://github.com/marikachrisanthopoulos/School_District_Analysis/blob/main/Resources/Scores_by_School_Spending_Old.png)

**New Scores by School Spending**
![New Scores by School Spending](https://github.com/marikachrisanthopoulos/School_District_Analysis/blob/main/Resources/Scores_by_School_Spending_New.png)


**Old Scores by School Size**
![Old Scores by School Size](https://github.com/marikachrisanthopoulos/School_District_Analysis/blob/main/Resources/Scores_by_Size_Old.png)

**New Scores by School Size**
![New Scores by School Size](https://github.com/marikachrisanthopoulos/School_District_Analysis/blob/main/Resources/Scores_by_Size_New.png)



**Old Scores by School Type**
![Old Scores by School Type](https://github.com/marikachrisanthopoulos/School_District_Analysis/blob/main/Resources/Scores_by_Type_Old.png)

**New Scores by School Type**
![New Scores by School Type](https://github.com/marikachrisanthopoulos/School_District_Analysis/blob/main/Resources/Scores_by_Type_New.png)

## Summary

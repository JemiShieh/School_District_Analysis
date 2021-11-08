# School District Analysis

## School District Analysis Overview
Assist Maria, the Chief Data Scientist for the PyCity School District, in analyzing data to help the school board and superintendent make strategic decisions regarding future school budgets and priorities based on the standardized test scores and current school funding.

Use open-source distribution software called Anaconda and the Jupyter Notebook to analyze and visualize data from the schools_complete and students_complete CSV files to complete the following:

1. Replace certain math and reading scores due to academic dishonesty
2. The school district summary
3. The school summary
4. The top 5 and bottom 5 performing schools, based on the overall passing rate
5. The average math score for each grade level from each school
6. The average reading score for each grade level from each school
7. The scores by school spending per student
8. The scores by school size
9. The scores by school type

## School District Analysis Resources

* Data Sources: schools_complete.csv, students_complete.csv
* Software: Anaconda 4.10.3, Python 3.7.1, Jupyter Notebook 6.4.5

## School District Analysis Results

* How is the district summary affected?
  - Average math scores decreased from 79.0 to 78.9, average reading scores remained the same 81.9, % passing math decreased from 75.0 to 74.8, % passing reading decreased from 85.8 50 85.7, and % overall passing decreased from 65.2 to 64.9. 
        
* How is the school summary affected?
  - Average math scores decreased from 83.42 to 83.35, average reading scores increased 83.84 to 83.89, % passing math decreased from 93.3 to 93.2, % passing reading decreased from 97.3 to 97.0, and % overall passing decreased from 90.9 to 90.6.
 
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - Thomas High School remains the second-best performing school based on the overall passing percentage.      
  
* How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade - Only the Thomas High School ninth grade math and reading scores were affected, going from 83.6 and 83.7, respectively, to Nan.  
  
  - Scores by school spending - There were no significant changes, even to the $633-644 spending range including Thomas High School.
            
  - Scores by school size - There were no significant changes, even to the Medium school size range including Thomas High School.
            
  - Scores by school type - There were no significant changes, even to the Charter school type range including Thomas High School.

## School District Analysis Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. Tomas High School ninth grade math and reading scores are no longer included in the average score and passing percentage calculations.  
2. Average math scores decreased from 83.42 to 83.35
3. Average reading scores increased 83.84 to 83.89
4. % passing math decreased from 93.3 to 93.2 
5. % passing reading decreased from 97.3 to 97.0 
6. % overall passing decreased from 90.9 to 90.6

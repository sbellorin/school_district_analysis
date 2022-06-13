# school_district_analysis
PyCitySchools with Pandas

## Main Objective
1. Open Jupyter Notebook files from local directories using a development environment.
2. Read an external CSV file into a DataFrame.
3. Format a DataFrame column.
4. Determine data types of row values in a DataFrame.
5. Retrieve data from specific columns of a DataFrame.
6. Merge, filter, slice, and sort a DataFrame.
7. Apply the groupby() function to a DataFrame.
8. Use multiple methods to perform a function on a DataFrame.
9. Perform mathematical calculations on columns of a DataFrame or Series.

## Project Overview
Maria is the chief data scientist for a city school district. She has requested an analysis of school spending and standardized test scores.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.6.9, Anaconda Navigator 1.9.7, Jupyter Notebook 6.0.1

### How is the district summary affected?

When comparing the two charts, removing less than 500 test scores had a nominal impact on the almost 40,000 student data set.  The average math score decreased by 0.1 points while the average reading score stayed the same.  The percentage of students passing math decreased by 1% as did the percentage of students passing reading. The overall passing percentage also decreased by 1%.

### How is the school summary affected?

In the original analysis, Thomas High School started with a 91% overall passing rate.  After calculating the total number of 10th - 12th grade students the overall math and reading passing numbers decreased by dropping from 91% to 65% for the overall passing rate. 

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
In the original analysis, Thomas High School ranked 2nd in the district overall with a passing % of ~92% down to last place with a passing % of ~68%.

## How does replacing the ninth-grade scores affect the following:

### Adjusted Averages using the Math and Reading Scores 
Thomas High School's 9th grade class has no math or reading score data to count.
Now the scores have been replaced with null values and shows up in Python programming as NaN in the following charts. 

### Scores by school spending

Thomas High School falls in the $630-$644/student spending range. 

### Scores by school size
Thomas High School is defined as a medium sized school.  
There was very little impact by campus size due to changing the 9th grade scores. 

### Scores by school type

Thomas High School is a charter school type. The Charter schools saw a decrease in the passing percentages since THS was in that school type. The average math and reading scores for that range remained the same.


## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. The overall passing rate for Thomas High School declined from 91% to 65%. 

2. Thomas High School's ranking dropped from 2nd to 8th in the district. 

3. Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School  

4. The campus math and reading averages and passing percentages all saw shifts.  

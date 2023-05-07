# Pandas_Challenge

PyCity Schools Analysis :

1) As a whole, schools with higher budgets, did not yield better test results than schools with lower budge.

2) Smaller and medium sized schools dramatically out-performed large sized schools on passing math performances.

3) Charter schools out-performed the public district schools across all metrics. However, more analysis will be required to   determine if the effect is due to school practices or the fact that charter schools tend to serve smaller student populations per school.
----------------------------------------------------------------------------------------------------------------------------
District Summary :

Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame. Include the following: Total number of unique schools Total students Total budget Average math score Average reading score % passing math (the percentage of students who passed math) % passing reading (the percentage of students who passed reading) % overall passing (the percentage of students who passed math AND reading)

School Summary :
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school. Include the following: School name School type Total students Total school budget Per student budget Average math score Average reading score % passing math (the percentage of students who passed math) % passing reading (the percentage of students who passed reading) % overall passing (the percentage of students who passed math AND reading)

Highest-Performing Schools (by % Overall Passing) : 
Sort the schools by % Overall Passing in descending order and display the top 5 rows. Save the results in a DataFrame called "top_schools".

Lowest-Performing Schools (by % Overall Passing) : 
Sort the schools by % Overall Passing in ascending order and display the top 5 rows. Save the results in a DataFrame called "bottom_schools".

Math Scores by Grade : 
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade : 
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending :
Create a table that breaks down school performance based on average spending ranges (per student). Use the code provided below to create four bins with reasonable cutoff values to group school spending. Use the scores to create a DataFrame called spending_summary. Include the following metrics in the table: Average math score Average reading score % passing math (the percentage of students who passed math) % passing reading (the percentage of students who passed reading) % overall passing (the percentage of students who passed math AND reading)

Scores by School Size : 
Use pd.cut with the provided code to bin the data by the school sizes Use the code provided to calculate the averages Create the size_summary DataFrame using the binned and averaged size data

Scores by School Type : 
Group the per_school_summary DataFrame by "School Type" and average the results Use the code provided to select the new column data Create a new DataFrame called type_summary that uses the new column data

Draft a written Analysis : 
Summarizes the analysis Draws two correct conclusions or comparisons from the calculations

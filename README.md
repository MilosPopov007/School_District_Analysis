# School_District_Analysis
 The Analysis presents  aggregated data and showcase trends in school performance using Pandas software library  and Jupyter Notebook ( web-based interactive computing platform).
## Analysis steps 
Analyzing information from a variety of sources and using the Pandas read_csv function and the os module I created a DataFrame called student_df.
My main purpose was to analyze data on student funding and students' standardized test scores (student's math and reading scores) as well as various information on the schools they attend.
Analysis steps :
*  Collect the Data - Using the Pandas read_csv function and the os module, imported the data from the new_full_student_data.csv file, and created a DataFrame called student_df.
*  Prepare the Data - this step includes preparing  and cleaning  data for analysis
*  Summarize the Data - describes the data, using summary statistics on the data as a whole and on individual columns
*   Drill Down into the Data - drilling down to specific rows, columns, and subsets of the data using "iloc" and "loc" function
*   Make Comparisons - Compares district vs. charter schools for budget, size, and scores using "groupby", "count" and "mean" functions
### Results
Students overall preformed better on their reading test than on the mathematics test, this includes both Charter and Public schools. Student in Charter schools had better results on their mathematical tests vs. students in Public schools. School budget for Public schools was slightly higher than in the Charter schools.
We may conclude that students in Charter schools performed better on their tests than students in Public schools, but in support of this analysis, it is suggested that we consider an additional analysis that will include individual schools and the number of students for a more comprehensive analysis.

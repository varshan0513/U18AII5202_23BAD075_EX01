Visualization of Academic Performance Indicators Using R

Name: Navin Varshan R
Roll No: 23BAD075

Objective

To analyze and visualize the internal assessment performance of first-year engineering students across multiple subjects using appropriate data visualization techniques in R.

Software and Tools Used

R Version: 4.4.1

R Packages:

ggplot2

dplyr

tidyr

Dataset Description

File Name: 1.student_performance.csv

Description:
The dataset contains internal assessment details of students, including:

Roll Number

Subject

Internal Test 1 Marks

Internal Test 2 Marks

Assignment Marks

Final Grade

Steps Performed
1. Load Required Libraries

Necessary libraries for data manipulation and visualization are loaded using the library() function.

2. Import Dataset

The dataset is imported into R using the read.csv() function.

3. Data Preprocessing

A new column, Average_Marks, is computed by calculating the mean of:

Internal Test 1 Marks

Internal Test 2 Marks

Assignment Marks

4. Data Visualization
a) Bar Chart – Subject-wise Average Marks

Displays the average internal marks for each subject.

Helps identify subjects with lower overall performance.

b) Line Chart – Performance Trend Across Tests

Shows the trend of average student performance across internal tests.

Useful for analyzing improvement or decline in performance over time.

c) Pie Chart – Grade Distribution

Represents the distribution of final grades among students.

Provides a clear overview of overall academic outcomes.

Output Generated

Bar chart showing subject-wise average marks

Line chart depicting performance trends across internal tests

Pie chart illustrating grade distribution

(Screenshots of the code and outputs are included separately.)

Conclusion

The visualization techniques used in this analysis effectively highlight subject difficulty levels, performance trends, and grade distribution. Such insights can help academic institutions identify weak areas and improve teaching and evaluation strategies.

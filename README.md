![Cover photo](screen%20shoots/education.png)

# Panda-Challenge :panda_face:
*In this assignment, I’ll create and manipulate Pandas :panda_face: DataFrames to analyse school :student: and standardised test data.*
# Background
You are the new Chief Data Scientist for your local government area. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyse the area-wide standardised test results. You'll be given access to every student's maths and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance.
#### Objectives
The purpose of this challenge is to create a script using Pandas and Jupyter Notebook that analyses school records based on a dataset provided. The aim is to create a code that calculates each of the following values:

![Screen Shot of Main Analysis](/firstanalysis.png)
###### Local Government Area (LGA) Summary
Perform the necessary calculations and then create a high-level snapshot of the local government area's key metrics in a DataFrame.

* Total number of unique schools
* Total students
* Total budget
* Average maths score
* Average reading score
* % passing maths (the percentage of students who passed maths)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed maths AND reading)

*Step by step:*
* I started a script ensuring all the dependencies are imported.
* Created a pathway to the csv file.
* Merged the files together.
* Calculated the required values (total number of schools, total number of students, total budget, average maths and reading score, % of passing for both mathemathcs and reading, and % of overall passing in both).
* Created the dataframe to hold my results.
* Copied the summary to keep the original for future reference.
* Set the right format.

![Screen Shot of local gov summary](/localgovsummary.png)

###### School Summary
Perform the necessary calculations and then create a DataFrame that summarises key metrics about each school.
Include the following:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average maths score
* Average reading score
* % passing maths (the percentage of students who passed maths)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed maths AND reading)

![Screen shot of School Summary](/schoolsummary.png)


*Step by step:*
* I sourced required information from the provided file.
* Filtered through the data as required.
* Sourced and calculated required values (School name, school type, total number of students, total school budget, per student budget, average math and reading scores, % percentage of maths and reading, and % of overall passing in both).
* Created the dataframe to hold my results.
* Copied the summary to keep the original for future reference.
* Set the right format.

![Screen Shot of the key metrics DF](/bigdataframe.png)

###### Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.
Save the results in a DataFrame called "top_schools"

*Step by step:*
* I used function sort.values in order to filter the data based on the % of Overall Passing.
* Ascended the values using conditional statement and displayed results.

![Screen Shot of the Top 5 performing Schools](/hps.png)

###### Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
Save the results in a DataFrame called "bottom_schools".

*Step by step:*
* I used function sort.values in order to filter the data based on the % of Overall Passing.
* Ascended the values using conditional statement and displayed results.

![Screen Shot of the Bottom 5 performing Schools](/lps.png)

###### Maths Scores by Year
Perform the necessary calculations to create a DataFrame that lists the average maths score for students of each year level (9, 10, 11, 12) at each school.

*Step by step:*
* I have separated data based on the year.
* Grouped the data based on the avreage score in maths.
* Created a dataframe to hold the results.
* Displayed the dataframe.

![Screen Shot of the Math Scores per Year](/msby.png)

###### Reading Scores by Year
Create a DataFrame that lists the average reading score for students of each year level (9, 10, 11, 12) at each school.

*Step by step:*
* I have separated data based on the year.
* Grouped the data based on the avreage score in reading.
* Created a dataframe to hold the results.
* Displayed the dataframe.

![Screen Shot of the Reading Scores per Year](/rsby.png)

###### Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).

Use the code provided below to create four bins with reasonable cutoff values to group school spending.

*Step by step:*
* Established the bins.
* Manipulated previous dataframe to display required values. 
* Created a copy of a new dataframe.
* Set new columns and assigned the bins accordingly.
* Grouped the data taking an average value based on Spending Ranges (per Student).
* Displayed the results.

![Screen Shot of the Scores by Spending](/schoolsbyspending.png)

###### Scores by School Size
Use the following code to bin the per_school_summary.

*Step by step:*
* Established the bins.
* Manipulated previous dataframe to display required values. 
* Created a copy of a new dataframe.
* Set new columns and assigned the bins accordingly.
* Grouped the data taking an average value based on Spending Ranges (per Student).
* Displayed the results.

![Screen Shot of the Scores by School Size](/sbs.png)

###### Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

This new DataFrame should show school performance based on the "School Type".

*Step by step:*
* Manipulated previous dataframe to display required values. 
* Created a copy of a new dataframe.
* Filtered through the data and grouped the results.
* Displayed the outcomes.

![Screen Shot of the Scores by School type](/sbst.png)


#### Technologies used
* *Visual Studio Code - **Jupyter Notebook**
* *Excel* 
* *GitHub* 
* **Pandas**


#### File list
* PyCitySchools_solved.ipynb
* schools_complete.csv - resources file containing dataset
* students_complete.csv - resources file containing dataset
* Various Screen Shots


# Student-Data
An interactive Power BI dashboard for analyzing student performance. The project includes data cleaning, star schema modelling, and DAX calculations to measure pass and fail rates and the teacher-to-student ratio. Interactive visuals provide insights into performance across students, schools, teachers, and subjects.

**Data Cleaning**
There was inconsistent data in the text fields, so we converted the cases into a proper format. We also removed the Created On column, all the country columns because they contained the same data, the term column and other unnecessary columns.

**Data Modelling**
We used a star schema, where we had a fact table and dimension tables for Students, Schools, Subjects, and Teachers. The primary keys were School ID, Student ID, Teacher ID, Subject ID, and Record ID.

**Measures and DAX**
We created a new column called Score Category to classify the scores using the average score as the reference. Values greater than the average score were classified as Pass, while those less than the average were classified as Fail. This was useful in finding the pass and fail rates. The teacher-to-student ratio was found by dividing the number of students by the number of teachers.
We were not able to find the revenue collected because we only had a column showing fee balances and not the actual amount that each student was required to pay for the term.

**Analysis and Dashboard**
Different visualization tools were used to clearly present the different types of data that we had.

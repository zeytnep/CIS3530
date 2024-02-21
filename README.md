##README for Assignment 1<br>
#Learning Goals<br>
1.Be able to read and understand a given relational schema and its structure.<br>
2.Have mastered the techniques for writing relational algebra (RA) queries and basic SQL queries.<br>

#Question 1 (Relational Algebra):<br>
Write relational algebra expressions to answer the following questions:<br>

a. Find all offerings of 3530.

b. Find all CIS courses offered in 2016.

c. Find all courses offered by Ritu.

d. Find all students registered in 3530 in fall 2017.

e. Find all students who do not take course CIS3530.

f. Find students who take all 'HIS' courses offered.

g. Find all courses that have the same number but are offered by different departments.

h. Write a query that displays all courses and the term and year they are offered, if offered. The courses that are not offered must display NULL values for term and year.

i. Develop a query for this database, write its description/question in English (as given in questions 1a to 1h), give its solution and expected output. The query must involve at least 2 tables and at least 3 operators. You will be marked based on its originality and the operators used.

The file called A1Q1_erdogru_zeynep.txt that includes all the RA queries for questions 1a to 1i.

#Question 2 (SQL):<br>
Must run the attached scripts given in the 2 files coursesDDL.sql and coursesData.sql to create the tables on PostgreSQL required for this question. There are 12 queries to write for this question (a-l).<br>

a-h. Write SQL queries for question 1a-h.

i. Find all students who have taken CIS3530 multiple times.

j. Find all courses for the term F 2017 and the current enrollment.

k. Write a query to update table OFFERING such that course 3530 is always offered by 'Harry'.

l. Write a query that deletes all courses taught by 'Ritu'.

The file called A1Q2_erdogru_zeynep.sql that includes all the SQL queries for the questions.

#Question 3 (SQL):<br>
Attached SQL file called A1Q3_create.sql and 4 CSV files (females.csv, males.csv, married_to.csv, and parent_of.csv). Run the SQL file to create 4 tables required for this question. Then, on psql prompt, run \copy command on each of the CSV files to populate the tables.<br>

a-f. Write SQL queries for questions 1a to 1f.

The file called A1Q3_erdogru_zeynep.sql includes all the SQL queries for the questions.

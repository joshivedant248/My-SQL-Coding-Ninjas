SQL Query - 21

Problem Statement:
Fetch out the email ids of all students who joined in 2005 and sort them in descending order wrt date of birth of the students.

Information about the table:
Table Student:
![Image1](https://user-images.githubusercontent.com/97792024/184967311-e28e887a-5dfb-4a97-a365-8d92ef573af9.png)

QUERY-SELECT email FROM Student WHERE joining_Year=2005 ORDER BY DOB DESC;

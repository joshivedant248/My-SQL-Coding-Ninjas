SQL Query - 15

Problem Statement:
List down the complete names of the students from batch 2019 (who joined in 2019) and the second letter of their first name is “s”.

Information about the table:

Table Student:
![Image1](https://user-images.githubusercontent.com/97792024/184967311-e28e887a-5dfb-4a97-a365-8d92ef573af9.png)

QUERY- SELECT fname,lname FROM Student WHERE joining_YEAR=2019 AND SUBSTR(fname,2,1)='s'; 


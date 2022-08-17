SQL Query - 22

Problem Statement:
List out the complete name of all the students who enrolled in CS206 batch 2019 and sort them in ascending order according to their date of birth and lname.

Information about the table:
Table Student:
![Image1](https://user-images.githubusercontent.com/97792024/184967311-e28e887a-5dfb-4a97-a365-8d92ef573af9.png)

QUERY-SELECT fname,lname FROM Student WHERE course='CS206' AND joining_year=2019 ORDER BY DOB;


SQL Query - 4

Problem Statement:
List down all the student's personal details like student id, name and contact information like email, phone number who joined the institute after 2000 and have the surname Daga.

Information about the table:
Table Student:

![Image1](https://user-images.githubusercontent.com/97792024/184506923-9c238eed-ee1a-480c-a97f-024ff055e882.png)

Output Table Structure:
![Image2](https://user-images.githubusercontent.com/97792024/184507016-a2051420-01b0-4815-b98a-4375867a8ce0.png)

Note-1: Write keywords of syntax in uppercase alphabets.


Note-2: The name of values which are in form of strings (datatype), should be put inside single or double quote.

Query- SELECT stud_id,fname,lname,email,ph_no FROM Student WHERE lname='Daga' AND joining_year>2000;

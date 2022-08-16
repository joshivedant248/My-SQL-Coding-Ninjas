SQL Query - 7

Problem Statement:
List out all the students' names (fname and lname) with their joining year and phone number who were born on and after 2nd November 1998.

Information about the table:
Table Student:

![Image1](https://user-images.githubusercontent.com/97792024/184967311-e28e887a-5dfb-4a97-a365-8d92ef573af9.png)


Output Table Structure:
![Image2](https://user-images.githubusercontent.com/97792024/184967326-19690c37-e160-4b0a-aba6-3edb7c3ddaae.png)



Note: Write keywords of syntax in uppercase alphabets.

SELECT fname,lname,joining_Year,ph_no FROM Student WHERE DOB>='1998-11-02';

SQL Query - 18
Problem Statement:
List down all the employee id’s and names whose Email contains ‘bcd’ and belongs to department D3 or D4 but aren’t from Himachal, Guwahati.

Information about the table:
Attributes list: 
![tab-12520](https://user-images.githubusercontent.com/97792024/184972333-17560874-7027-4e39-90b2-ee50e03a5c57.png)






Table Emp_data:

![fsd_query9table-16178](https://user-images.githubusercontent.com/97792024/184971979-fda507f3-78a4-4a05-8ce4-ee4f602adac3.png)


QUERY-
SELECT Emp_ID, Emp_name FROM Emp_data WHERE Email LIKE '%bcd%' AND Dept IN('D3','D4') 
AND 
HomeTown NOT IN('Himachal','Guwahati');

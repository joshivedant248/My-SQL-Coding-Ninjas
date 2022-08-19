SQL query - 11

Problem Statement:
Fetch the Number of employees for each role/Job.


Note: Name the number of employees as "empnum" using Alias Keyword.

Information about the table:
Attributes list: 
Table Employee_data:


QUERY-SELECT Job, COUNT(EmpCode) AS empnum FROM Employee_data GROUP BY Job; 

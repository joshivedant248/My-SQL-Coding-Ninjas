SQL query - 11

Problem Statement:
Fetch the Number of employees for each role/Job.


Note: Name the number of employees as "empnum" using Alias Keyword.

Information about the table:
Attributes list: ![gd_query_11_table-16276](https://user-images.githubusercontent.com/97792024/185567089-d46b90be-7a9f-425d-bbac-087f50f9e405.png)
Table Employee_data:
![groupaa-14170](https://user-images.githubusercontent.com/97792024/185567103-88b0557a-7cd4-48b3-8639-7bc6e927d92b.png)


QUERY-SELECT Job, COUNT(EmpCode) AS empnum FROM Employee_data GROUP BY Job; 

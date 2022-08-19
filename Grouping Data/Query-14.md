SQL query - 14

Problem Statement:
List down the average salary given out for each department for specific job roles.

Information about the table:
Attributes list: 
![q-12536](https://user-images.githubusercontent.com/97792024/185599467-dbebbd4b-fac4-4989-a38d-8468f628d5c6.png)

Table Employee_data:
![gd_query_11_table-16276](https://user-images.githubusercontent.com/97792024/185567089-d46b90be-7a9f-425d-bbac-087f50f9e405.png)

QUERY-SELECT Job,DeptCode,AVG(Salary) FROM Employee_data GROUP BY Job,DeptCode;

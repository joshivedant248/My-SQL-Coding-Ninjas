QL query - 15
Problem Statement:
List down the minimum salaries offered for each job role in each department, also list them in descending order based on the max salaries being offered for that role.

Information about the table:
Attributes list:
![q-12536](https://user-images.githubusercontent.com/97792024/185599467-dbebbd4b-fac4-4989-a38d-8468f628d5c6.png)
Table Employee_data:
![gd_query_11_table-16276](https://user-images.githubusercontent.com/97792024/185567089-d46b90be-7a9f-425d-bbac-087f50f9e405.png)


Output :
The result set should have the job name, its department code and its corresponding minimum salary.

QUERY-SELECT Job,DeptCode,MIN(Salary) 
FROM Employee_data GROUP BY Job,DeptCode ORDER BY MAX(Salary) DESC;

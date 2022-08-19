SQL query - 13
Problem Statement:
List down the maximum salaries for each Job role

Information about the table:
Attributes list: 
![groupaa-14170](https://user-images.githubusercontent.com/97792024/185558470-e126f45b-bd06-4141-a2f9-f8304a3ee54d.png)
Table Employee_data:
![gd_query_11_table-16276](https://user-images.githubusercontent.com/97792024/185567089-d46b90be-7a9f-425d-bbac-087f50f9e405.png)


QUERY-SELECT Job,MAX(Salary) FROM Employee_data GROUP BY Job;

SQL query - 13
Problem Statement:
List down the maximum salaries for each Job role

Information about the table:
Attributes list: 
![q-12536](https://user-images.githubusercontent.com/97792024/185599467-dbebbd4b-fac4-4989-a38d-8468f628d5c6.png)

Table Employee_data:

![groupaa-14170](https://user-images.githubusercontent.com/97792024/185558470-e126f45b-bd06-4141-a2f9-f8304a3ee54d.png)

QUERY-SELECT Job,MAX(Salary) FROM Employee_data GROUP BY Job;

SQL Query - 2
Send Feedback
Problem Statement:
List the number of customers from each city.

Information about the table:
Table Customer :

![groupaa-14170](https://user-images.githubusercontent.com/97792024/185558470-e126f45b-bd06-4141-a2f9-f8304a3ee54d.png)

Output :
The result set should have 2 columns. 
The first column contains the city name and 2nd column should contain the corresponding number of customers. Rename the second column as Cust_num.

QUERY- SELECT City, COUNT(cname) AS cust_num FROM Customer GROUP BY City;

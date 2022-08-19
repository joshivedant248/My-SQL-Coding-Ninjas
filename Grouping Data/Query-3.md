SQL Query - 3

Problem Statement:
List out the total number of orders made to each address.

Information about the table:
Table Customer: 
![groupaa-14170](https://user-images.githubusercontent.com/97792024/185558470-e126f45b-bd06-4141-a2f9-f8304a3ee54d.png)

Output :
The result set should have the address and its corresponding sum of total orders made to that address.

QUERY-SELECT Address,SUM(TotalOrdersYet) FROM Customer GROUP BY Address;

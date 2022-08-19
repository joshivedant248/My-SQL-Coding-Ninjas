SQL Query - 5
Send Feedback
Problem Statement:
List out the minimum number of orders made from a particular Gender.

Information about the table:
Table Customer:

![groupaa-14170](https://user-images.githubusercontent.com/97792024/185558470-e126f45b-bd06-4141-a2f9-f8304a3ee54d.png)


Output :
The result set should have the Gender and its corresponding minimum number of orders.

QUERY-SELECT Gender, MIN(TotalOrdersYet) FROM Customer GROUP BY Gender; 

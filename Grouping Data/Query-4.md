SQL Query - 4
Send Feedback
Problem Statement:
List out the maximum number of orders made from a particular Pincode.

Information about the table:
Table Customer:
![groupaa-14170](https://user-images.githubusercontent.com/97792024/185558470-e126f45b-bd06-4141-a2f9-f8304a3ee54d.png)


QUERY-SELECT Pincode, MAX(TotalOrdersYet) FROM Customer GROUP BY Pincode;

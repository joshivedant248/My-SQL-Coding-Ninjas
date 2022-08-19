SQL Query - 7

Problem Statement:
List the cities in descending order of the number of customers residing in them.
Note: Name the number of customers residing in them as "Number" using Alias Keyword.

Information about the table:
Table Customer:
![groupaa-14170](https://user-images.githubusercontent.com/97792024/185558470-e126f45b-bd06-4141-a2f9-f8304a3ee54d.png)

QUERY-SELECT City,COUNT(cust_id) AS Number FROM Customer GROUP BY City ORDER BY COUNT(cust_id) DESC;

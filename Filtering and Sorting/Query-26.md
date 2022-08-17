SQL Query - 26

Problem Statement:
List down all the order details whose cost is less than 5000 , in ascending order by cost.

Information about the table:
Attributes list: 

![fsd_query23_al-16233](https://user-images.githubusercontent.com/97792024/185155870-72066056-a636-458e-891a-583649873cf8.png)

Table e_transactions:
![fsd_query23_table-16234](https://user-images.githubusercontent.com/97792024/185155938-27c40b3b-9f71-4e0c-ba12-a40307d6f640.png)

QUERY-SELECT * FROM e_transactions WHERE cost<5000 ORDER BY cost;

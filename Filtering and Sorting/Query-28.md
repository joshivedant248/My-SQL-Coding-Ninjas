SQL Query - 28

Problem Statement:
List down all the details of the orders made in February 2021 or July 2021, also sort them in ascending order by their price.

Information about the table:
Attributes list: 
![fsd_query23_al-16233](https://user-images.githubusercontent.com/97792024/185155870-72066056-a636-458e-891a-583649873cf8.png)


Table e_transactions:
![fsd_query23_table-16234](https://user-images.githubusercontent.com/97792024/185155938-27c40b3b-9f71-4e0c-ba12-a40307d6f640.png)

QUERY- SELECT * FROM e_transactions
WHERE ordered_time like '%-02-%' OR  ordered_time like '%-07-%' 
ORDER BY cost;

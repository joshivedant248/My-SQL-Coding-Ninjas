SQL Query - 27

Problem Statement:
List down the orders ids with their shipping time which were ordered before 30th June 2021 sort them in ascending order w.r.t. cost and in descending order w.r.t. time the purchase was made.

Information about the table:
Attributes list: 
![fsd_query23_al-16233](https://user-images.githubusercontent.com/97792024/185155870-72066056-a636-458e-891a-583649873cf8.png)

Table e_transactions:
![fsd_query23_table-16234](https://user-images.githubusercontent.com/97792024/185155938-27c40b3b-9f71-4e0c-ba12-a40307d6f640.png)
 
 QUERY-SELECT order_id,shipping_time FROM e_transactions 
WHERE ordered_time<'2021-06-30' ORDER BY cost, ordered_time DESC;

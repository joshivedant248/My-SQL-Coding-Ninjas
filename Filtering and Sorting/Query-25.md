SQL Query - 25
Problem Statement:
Fetch out all the records but in descending order by ordering time and in case of similar order times sort in ascending order w.r.t. shipping time.

Information about the table:
Attributes list: 
![fsd_query23_al-16233](https://user-images.githubusercontent.com/97792024/185155870-72066056-a636-458e-891a-583649873cf8.png)

Table e_transactions:
![fsd_query23_table-16234](https://user-images.githubusercontent.com/97792024/185155938-27c40b3b-9f71-4e0c-ba12-a40307d6f640.png)

QUERY-SELECT * FROM e_transactions ORDER BY ordered_time DESC,shipping_time;

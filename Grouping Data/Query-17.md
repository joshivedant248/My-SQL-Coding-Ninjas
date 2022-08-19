SQL query - 17
Problem Statement:
List down the addresses with the city and the pincode which appear more than twice in the table.

Information about the table:
Table Customer:
![groupaa-14170](https://user-images.githubusercontent.com/97792024/185567103-88b0557a-7cd4-48b3-8639-7bc6e927d92b.png)

QUERY-SELECT Address,City,Pincode FROM Customer GROUP BY Address,City,Pincode HAVING COUNT(*)>2;

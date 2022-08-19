SQL query - 18
Send Feedback
Problem Statement:
List down all the addresses which belong to Guwahati and have made more than 7 orders in total.

Information about the table:
Table Customer:
![groupaa-14170](https://user-images.githubusercontent.com/97792024/185567103-88b0557a-7cd4-48b3-8639-7bc6e927d92b.png)

QUERY-SELECT Address FROM Customer WHERE City='Guwahati' GROUP BY Address HAVING SUM(TotalOrdersYet)>7 ;

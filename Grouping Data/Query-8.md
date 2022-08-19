SQL Query - 8
Send Feedback
Problem Statement:
List down all the addresses from Jalandhar city with the number of times the address appears.
Note: Name the number of times the address appears as "Address_times" using Alias Keyword.

Information about the table:
Table Customer:
![groupaa-14170](https://user-images.githubusercontent.com/97792024/185558470-e126f45b-bd06-4141-a2f9-f8304a3ee54d.png)

QUERY- SELECT Address,COUNT(City) AS Address_times FROM Customer WHERE City='Jalandhar' GROUP BY Address;

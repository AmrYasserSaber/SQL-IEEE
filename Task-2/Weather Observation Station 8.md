# SQL-IEEE

select CITY from STATION
WHERE  city RLIKE '^[aeiouAEIOU].*[aeiouAEIOU]$'
GROUP BY CITY;
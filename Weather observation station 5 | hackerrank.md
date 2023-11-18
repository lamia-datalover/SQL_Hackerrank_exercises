## How to solve the following exercise of SQL section:
![sql10](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/ba635289-c1c3-40c5-9b1f-3588163ae82d)
## Solution of the exercise :
```bash
SELECT CITY, LENGTH(CITY) AS NameLength FROM STATION ORDER BY NameLength, CITY LIMIT 1;
SELECT CITY, LENGTH(CITY) AS NameLength FROM STATION ORDER BY NameLength DESC, CITY LIMIT 1;
```
## The exercise can be found in the following link :
https://www.hackerrank.com/challenges/weather-observation-station-5/problem

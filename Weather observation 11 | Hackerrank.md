## How to solve the following exercise of SQL section:
![sql16](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/29e8f2c4-6e4e-4bf7-ae6a-a665a22a4a79)

## Solution of the exercise :
```bash
Run it on MySQL
select distinct city from station where left(city,1) not in ('a','e','i','o','u') or right(city,1) not in ('a','e','i','o','u') ;
```
## The exercise can be found in the following link :
https://www.hackerrank.com/challenges/weather-observation-station-11/problem

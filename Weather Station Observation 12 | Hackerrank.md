## How to solve the following exercise of SQL section:
![sql17](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/4710cc5c-d452-46ca-a9da-506a2a9aed43)

## Solution of the exercise :
```bash
Run it on MySQL
select distinct city from station where not left(city,1) in ('a','e','i','o','u') and not right(city,1)  in ('a','e','i','o','u');
```
## The exercise can be found in the following link :
https://www.hackerrank.com/challenges/weather-observation-station-12/problem

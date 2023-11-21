## How to solve the following exercise of SQL section:
![sql13](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/9bcefefb-a59e-4fde-9939-8bd562029e2d)

## Solution of the exercise :
```bash
Run it on MySQL
select distinct city from station where left(city,1)in('a','e','i','o','u')and right(city,1) in ('a','e','i','o','u');
```
## The exercise can be found in the following link :
https://www.hackerrank.com/challenges/weather-observation-station-8/problem

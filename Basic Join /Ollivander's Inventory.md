# Here is the solution of the following exercise
![28](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/662eb967-42b8-4d3d-a322-4df046d5c18e)
# Solution:
```bash
SELECT t2.id, t1.age, t2.coins_needed, t1.power
FROM
    (SELECT MIN(coins_needed) AS min_coins, age, power, code
    FROM wands NATURAL JOIN wands_property
    WHERE is_evil = 0
    GROUP BY age, power, code) t1 JOIN wands t2 ON t1.code = t2.code AND t1.min_coins = t2.coins_needed
ORDER BY t1.power DESC, t1.age DESC;
```

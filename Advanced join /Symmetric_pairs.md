# Here is the solution of the following exercise:
![31](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/0df3be7d-b349-4a8f-9d66-11c335ccb8de)

# Solution :
```bash
SELECT * FROM Functions f1
WHERE EXISTS (SELECT * FROM Functions f2 WHERE f2.x = f1.y AND f2.y = f1.x)
GROUP BY x, y
HAVING x < y OR COUNT(*) > 1
ORDER BY x;
```

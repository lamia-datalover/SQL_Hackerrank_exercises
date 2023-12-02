# Here is the solution of this SQL exercise:
![sql22](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/4db4027f-5a7b-478e-baa6-35f835f62da0)
# Solution:
```bash
Run this query on MYSQL:
SELECT
    MAX(CASE WHEN occupation = 'Doctor' THEN name END),
    MAX(CASE WHEN occupation = 'Professor' THEN name END),
    MAX(CASE WHEN occupation = 'Singer' THEN name END),
    MAX(CASE WHEN occupation = 'Actor' THEN name END)
FROM (SELECT *, ROW_NUMBER() OVER(PARTITION BY occupation ORDER BY name) AS Table_1 FROM occupations) AS Table_2
GROUP BY Table_1 ;
```
# Link of the exercise:
https://www.hackerrank.com/challenges/occupations/problem

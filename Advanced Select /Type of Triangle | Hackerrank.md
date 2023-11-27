# Here is the solution of the following SQL exercise:
![21](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/94aefe75-acba-4d91-a50c-78ce57261abc)
# Solution :
```bash
SELECT 
    CASE 
        WHEN (A + B) <= C OR (B+C) <= A OR (C+A) <= B THEN 'Not A Triangle' 
        WHEN A = B AND B = C AND C = A THEN 'Equilateral'
        WHEN A = B OR B = C OR A = C THEN 'Isosceles' 
        WHEN A != B AND B != C AND A != C THEN 'Scalene' 
    END 
FROM TRIANGLES;
```
# Link to find the exercise:
https://www.hackerrank.com/challenges/what-type-of-triangle/problem

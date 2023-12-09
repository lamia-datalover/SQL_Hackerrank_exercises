# Here is the solution of this exercise :
![sql26](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/b750a19e-88b3-4ef9-9ad3-c71eb3b191d4)
![26 prime](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/734b20ca-8137-4a72-a2b4-080c38333a5d)
# Solution:
```bash
SELECT
    CASE 
        WHEN G.GRADE<8 THEN 'NULL'
        ELSE S.NAME
    END AS NAME,
    G.GRADE,
    S.MARKS
FROM STUDENTS AS S
LEFT JOIN GRADES AS G ON S.MARKS BETWEEN G.MIN_MARK AND G.MAX_MARK
ORDER BY G.GRADE DESC, S.NAME,  S.MARKS;
```

# Here is the solution of the following exercise:
![sql22](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/9188fdbe-4148-43a6-bc9f-a00c1a5ff7cf)
# Solution:
```bash
Run in MYSQL
SELECT N,
    CASE 
        WHEN P IS NULL THEN "Root"
        WHEN N IN (SELECT P FROM BST) THEN "Inner"
        ELSE "Leaf"
    END
FROM BST
ORDER BY N;
```
# Link of the exercise:
https://www.hackerrank.com/challenges/binary-search-tree-1/problem?isFullScreen=true

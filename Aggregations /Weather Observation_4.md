# Here is the solution of the following exercise:
![42](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/fa930740-e1a7-4fa9-aa3b-585f2394c0cb)
# Solution:
```bash
SELECT ROUND(LONG_W,4) FROM STATION
WHERE LAT_N=(SELECT MAX(LAT_N) FROM STATION WHERE LAT_N < 137.2345);
```

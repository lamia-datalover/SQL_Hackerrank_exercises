# Here is the solution of the following exercise:
![45](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/f3235821-10ea-4a7c-a723-4d4b554a1d80)
# Solution:
```bash
select round(LONG_W, 4) 
from STATION 
where LAT_N=(select min(LAT_N) from STATION where LAT_N > 38.7780  );
```

# Here is the solution of the following SQL exercise:
![sql24](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/a7aaec6f-3577-4288-9e70-e6989670a2c2)
![23prime](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/84605309-31b4-44a7-af54-9f05c0d572bd)
# Solution:
```bash
select C.NAME from CITY C 
left join COUNTRY B 
on C.COUNTRYCODE=B.CODE 
where B.CONTINENT='Africa';
```
# Link of the exercise:
https://www.hackerrank.com/challenges/african-cities/problem?isFullScreen=true

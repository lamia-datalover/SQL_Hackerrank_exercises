# Here is the solution of the following SQL exercise :
![sql23](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/d4b3de69-76db-4daa-b393-a1dc823b56e9)
![23prime](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/203270ae-8b59-4789-823b-0df306b81017)
# Solution :
```bash
select sum(C.POPULATION) from CITY C left join COUNTRY B on C.COUNTRYCODE = B.CODE where B.CONTINENT='Asia'; 
```
# Link of the exercise :
https://www.hackerrank.com/challenges/asian-population/problem?isFullScreen=true

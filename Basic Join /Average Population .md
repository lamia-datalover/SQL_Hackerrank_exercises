# Here is the solution of the following SQL exercise:
![sql25](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/7136ec2e-d91e-4728-8a3c-e6c09979d392)
![23prime](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/bae7423f-2b5b-4e47-8480-703623d2b81b)
# Solution :
```bash
select C.CONTINENT, FLOOR(AVG(B.POPULATION)) as num_pop 
from CITY B 
inner join  COUNTRY C
on C.CODE=B.COUNTRYCODE
group by C.CONTINENT;

```
# Link of the exercise :
https://www.hackerrank.com/challenges/average-population-of-each-continent/problem

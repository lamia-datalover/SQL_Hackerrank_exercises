# Here is the solution of SQL exercise:
![21](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/95e153e6-846d-4c1e-90bb-9d6928083fa7)
# Solution:
```bash
RUN IT ON MYSQL
select concat(Name,'(',left(Occupation,1),')') from OCCUPATIONS order by Name; 
select concat('There are a total of'," ",count(occupation)," ",lower(occupation),'s.') as total from OCCUPATIONS group by occupation order by total;

```
# Link of the following exercise:
https://www.hackerrank.com/challenges/the-pads/problem

# Here is the solution of this exercise :
![24](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/5705a2c4-34c1-4c16-9e08-20e6acfbf4e9)

# Solution:
```bash
select e.company_code, c.founder, count(distinct lead_manager_code), count(distinct senior_manager_code), count(distinct manager_code), count(distinct employee_code) 
from employee e 
left join company c on c.company_code = e.company_code 
group by e.company_code, c.founder 
order by e.company_code;
```
# Link of the exercise:
https://www.hackerrank.com/challenges/the-company/problem

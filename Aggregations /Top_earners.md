# Here is the solution of the following exercise:
![39](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/66890229-1a05-4e7a-acb9-73d04333ea0a)

# Solution:
```bash
select MAX(salary*months) , Count(employee_id)  from employee where (salary*months) = (select MAX(salary*months) from employee);
```

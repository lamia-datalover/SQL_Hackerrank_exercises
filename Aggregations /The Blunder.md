# Here is the solution of the following exercise:
![38](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/3592262e-6a74-4412-82b9-42f726630b30)

# Solution:
```bash
/*
Explanation : ceil function is used to round up the result to the nearest integer, replace function is used to replace any 0 in the salary with space .
This expression subtracts the average of the modified salaries (without zeros) from the actual average salary. This difference gives an insight into how the average salary is affected by the zeros in the salary figures
*/
select ceil (avg(salary) - avg((replace(salary, '0', '')))) from employees;

```

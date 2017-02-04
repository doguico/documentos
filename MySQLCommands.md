# MySQLCommands

- AVERAGE: SELECT AVG(salary)

- BETWEEN: 
 - WHERE salary BETWEEN 10000 AND 15000;
 - WHERE department_id IN (30, 100)

- CONCAT: SELECT  CONCAT(first_name,' ', last_name) 'Employee Name' 

- COUNT: SELECT COUNT(*)

- DATE:
 - YEAR(hire_date)
 - MONTH(hire_date)
 - DAY(hire_date)

- DIFFERENCE: SELECT MAX(salary) - MIN(salary) DIFFERENCE

- DISPLAY NAME: SELECT first_name "First Name"

- LENGTH: SELECT first_name,last_name, LENGTH(first_name)+LENGTH(last_name)  'Length of  Names' 

- LIKE: WHERE YEAR(hire_date)  LIKE '1987%';

- LIMIT OUTPUT: SELECT employee_id, first_name  FROM employees  LIMIT 10;

- MAX AND MIN: SELECT MAX(salary), MIN(salary) 

- MULTIPLYING: SELECT salary*.15 PF 

- SUBSTRING: SELECT SUBSTRING(first_name,1,3) 

- SUM: SELECT SUM(salary) 

- TRIM: SELECT TRIM(first_name)

- UNIQUE: SELECT DISTINCT department_id 

- UPPER: SELECT UPPER(first_name) 


## MISC

- SELECT COUNT(DISTINCT job_id) 

- SELECT 171*214+625 Result;

- SELECT * FROM employees WHERE  first_name REGEXP  '[0-9]';

-  WHERE job_id <> 'IT_PROG' 
- =  >  <  >=  <=  <>  !=


## References
- https://dev.mysql.com/doc/refman/5.7/en/comparison-operators.html

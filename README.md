# N26-Task-Solution

Please note the following points:
For the first task, I have NOT assumed any filters('is_blocked','is_active') since it was not mentioned in the requirements
The SQL solution is executable in BigQuery

Following steps were ensured(/can be used) for query optimization:
Use necessary filters
CTE preference over subqueries
Select specific fields instead of ‘select *’
Use of ‘group by’ over ‘select distinct’
Avoid using too many joins in same query
Preference of use of partitioned tables
Use inner join over conditions with ‘where’

Download Link https://programming.engineering/product/write-sql-queries-for-the-11-questions-at-the-end-of-this-assignment/

Write SQL queries for the 11 questions at the end of this assignment. Use these four data files:

data_depts

data_emps

data_manages

data_worksFor

and this script to load the database:

createEmpDeptManages

Don’t forget to change the paths for the load_data statements.

For each question, upload a .txt or .pdf file showing the question, your query, and the output. Please list your answers in the same order as the questions. If you do not have an answer for a question, just state the question and add “No answer” after it.

For example:

If there were a question Q99 like:

Q99: Find the name and salary of 22-year-old employees who live in Alaska (‘AK’) and earn more than $70,000.

Then your file should contain

Q99: Find the name and salary of 22-year-old employees who live in Alaska (‘AK’) and earn more than $70,000.

select *

from employee E

where E.age = 22 and E.residenceState = ‘AK’ and E.salary > 70000 ;

+——
	

+———–
	

+——
	

+——–
	

+—————-
	

+————
	

+

| eid
	

| name
	

| age | salary | residenceState | startDate |

+——
	

+———–
	

+——
	

+——–
	

+—————-
	

+————
	

+

| 1866 | Sally1866 |
	

22 |
	

75626 | AK
		

| 2017-07-18 |

+——
	

+———–
	

+——
	

+——–
	

+—————-
	

+————
	

+

1 row in set (0.00 sec)

======= Questions ========

Q1: Find all information about managers who are 25 years old or younger and live in California (‘CA’).

Q2: Find the name, salary, age, and residence state of all 20-year-old or younger managers who live in Indiana (‘IN’).

Q3: Find the names and salary of 25-year-old employees who work for departments located on the fourth floor in Alaska (‘AK’).

Q4: Find the name, salary, and EID of 49-year-old employees who work for a department located in Alaska (‘AK’) but live in California (‘CA’).

Q5: Find the total number of employees.

Q6: Find the number of employees who are managers.

Q7: Find the number of employees who are not managers.

Q8: Find the (eid,number) pair for employees who are managing two or more departments where “number” is the number of departments they are managing.

Q9: Present the (name1, salary1, name2, salary2), where salary1 is the salary of the employee with name1 and salary2 corresponds with name2, of all employee pairs where both are living in California (‘CA’), one is a 24-year-old manager, the other (who can be any age) is not a manager, and the manager earns more than three times the other employee.

Q10: For each department in Alaska (‘AK’) that has 25 or more employees working for it and a supply budget < $7,000, present the did, budget, and number of employees that work in that department.

Q11: For each state, present the salary of the average 20-year-old manager (i.e., average salary of mangers who are 20 years old) who lives in that state and the number of such managers.

Note: Your results can omit states that do not have any 20-year-old managers living in them.

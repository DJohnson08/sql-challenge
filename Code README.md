Most of the code I used was using examples from class for pulling these multiple databases together. SQL is much more forgiving than what we've done in JuypterLab the last month. 

Mainly using SELECT, FROM, JOIN, to pull from these databases were very easy to make these tables through PGAdmin instead of raw code we've done earlier. 

Basic Employee Information:

Retrieves employee details (ID, name, gender, salary) by joining the employees and salaries tables.
Employees Hired in 1986:

Lists the first name, last name, and hire date of employees hired during the year 1986, using a date filter.
Department Managers:

Fetches the managers for each department, including department details and manager names, by joining dept_manager, employees, and departments.
Employee Department Assignments:

Displays the department number, department name, and employee details for all employees by joining dept_emp, employees, and departments.
Specific Employee Search:

Finds employees whose first name is "Hercules" and whose last name starts with "B" using a combination of equality and wildcard (LIKE) filters.
Employees in the Sales Department:

Lists employees working in the Sales department by filtering based on department name.
Employees in Sales and Development:

Retrieves employees from both Sales and Development departments by filtering with an IN clause.
Employee Last Name Frequency:

SQL features like joins, filters, and aggregations to provide meaningful insights and reports. Calculates and sorts the frequency of each last name across all employees, showing how many employees share each last name, in descending order.t

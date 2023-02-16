# 12. SQL Challenge: Employee Tracker
​
## Description 

This command-line application is a Content Management System(CMS) that allows business owners to view and manage the departments, roles, and employees in a company so that they can organize and plan their business.

When the application is started, the user is presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role.

When choosing to view all departments, the user is presented with a formatted table showing department names and department ids.

When choosing to view all roles, the user is presented with the job title, role id, the department that role belongs to, and the salary for that role.

When choosing to view all employees, the user is presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to.

When choosing to add a department, the user is prompted to enter the name of the department and that department is added to the database.

When choosing to add a role, the user is prompted to enter the name, salary, and department for the role and that role is added to the database.

When choosing to add an employee, the user is prompted to enter the employee’s first name, last name, role, and manager and that employee is added to the database.

When choosing to update an employee role, the user is prompted to select an employee to update and their new role and this information is updated in the database.

This application was built with Node.js Inquirer package to interact with users at the command line, MySQL2 package to connect to the MySQL database and perform queries, and console.table package to print MySQL rows to the console.
​
A good one takes advantage of the opportunity to explain and showcase what your application does, justify the technologies used, and even talk about some of the challenges you faced and features you hope to implement in the future. A good README helps you stand out among the large crowd of developers putting their work on GitHub.

​
At a minimum, your project README needs a title and a short description explaining the what, why, and how. What was your motivation? Why did you build this project? (Note: The answer is not "Because it was a homework assignment.") What problem does it solve? What did you learn? What makes your project stand out? 

## Table of Contents
​
* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)

​
​
## Installation
​
Clone the repository, navigate to the project folder on your CLI and run the following command to install Node.js:

```npm install```
​

Run the following command on your CLI to run the application:

```node index.js```

Follow the prompts to create your company database!

Video Demonstration: https://youtu.be/Zqo4QObZ0s0

## Credits
* Inquirer package https://www.npmjs.com/package/inquirer
* MySQL2 package https://www.npmjs.com/package/mysql2
* console.table package https://www.npmjs.com/package/console.table


# Question
Write a C program that reads department information into an array of structure and employee information into another array of structure. 
According to department salary increase information, increase the employee’s current salary to new salary. 
•	Define a structure for a department. Each department should have an ID, name and salary increase percentage information (this value should be between 0-100).
•	Define a structure for an employee. Each employee should have ID, name, surname, current salary, department name and new salary information. 
The department name component should be defined as char. DO NOT define it as inner structure.
•	Create a function to calculate the new salary of each employee.

In the main program:
•	Input the number of departments (dept_n).
•	Input the total number of employees (employee_n).
•	Read information of departments (ID, name and salary increase) into an array of structure.
      o	  Salary increase value should be checked, in order to force user to enter a number between 1 and 100.
•	Read information of employees (ID, name, surname, current salary and department name) into array of another structure.
•	Call the function to find the new salary of each employee.
•	Change every employees name and surname as “Name S.” as shown in the sample run.
•	Output the new salaries of employees who has increase in the salary as seen in sample run.
•	Output the number of employees who do not have any increase in the salary.

In the function:
•	Write a function named increase_salary which gets four parameters, department D as array structure, employees E as array structure, 
size of department array and size of employee array.
•	This function should compare department name component of employee array of structure and name component of department array of structure; 
if they have same name new salary of employee should be calculated by below formula:
      o	New salary = current salary * salary increase / 100

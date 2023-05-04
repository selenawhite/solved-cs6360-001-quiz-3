Download Link: https://assignmentchef.com/product/solved-cs6360-001-quiz-3
<br>
<strong>Database Design </strong>

<strong> </strong>







Specify following queries in SQL. Use COMPANY database.




<ol>

 <li>Create following views.</li>

 <li>A view that has the department name, manager name, and address for every department.</li>

 <li>A view that has the employee name, supervisor name, and employee salary for each employee who works in the ‘Research’ department.</li>

</ol>




<ol start="2">

 <li>For each employee, list his/her ssn, last name and the number of dependents he/she has, even if it is zero (Output: Ssn, LName, Num Deps). Output should be ordered alphabetically, by last name of employee.</li>

</ol>




<ol start="3">

 <li>Find the last names of employees earning above average salary in their respective departments. (Output: Lname, DNo, Salary).</li>

</ol>




<ol start="4">

 <li>List the last names of employees who do not work on any project controlled by their respective departments (Output: LName).</li>

</ol>




<ol start="5">

 <li>List the female employees, each of whom works on 2 or more projects. (Output: SSN, Number-of-projects)</li>

</ol>




Each question is 20 points.













<em>If you are not using Oracle Cloud account to test your sql queries, use following schema for COMPANY database.</em>







Employee (FName, LName, <u>SSN</u>, BDate, Address, Gender, Salary, SuperSSN, DNo)




Department (DName, <u>DNo</u>, MgrSSN, MgrStartDate)




Project (PName, <u>PNo</u>, PLocation, DNo)




Works_On (<u>SSN</u>, <u>PNo</u>, Hours)




Dept_Location (<u>Dno</u>, <u>DLocation</u>)




Dependent (<u>Essn</u>, <u>Name</u>, Gender, Relationship)



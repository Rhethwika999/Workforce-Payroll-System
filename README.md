# Workforce-Payroll-Management-System
The project focuses on developing an efficient Payroll Management System using the NYC Payroll dataset. The system is designed to streamline the tracking, analysis, and reporting of employee salaries and related financial information, ensuring accurate and organized payroll management.

### Summary: 
1. Employee Information :
Maintaining accurate employee data is essential for communication, event invitations, and collecting 
feedback. 
2. Salary Records :
Tracking salary details helps HR and management monitor payroll and enables the company to assess 
employee costs. 
3. Work Location :
Recording work locations supports regional growth planning, targeted hiring, and market expansion 
strategies. 
4. Projects :
Maintaining project records, including employee assignments and related salaries, ensures smooth project 
management and cost analysis.


### PL/SQL Features Used in the Project: 
1. Designed Explicit Cursors to display employees' hourly pay linked to their respective accounts, and 
implemented a Ref Cursor to retrieve employees belonging to a specific department. 
2. Created a Container Database (CDB) and Pluggable Database (PDB) with users to efficiently manage data 
based on specific areas of interest. 
3. Implemented the pre-defined exception CURSOR_ALREADY_OPEN to demonstrate exception handling by 
showing the error triggered when opening an already open cursor. 
4. Developed Relational Views, Inline Views, and Materialized Views to meet diverse business 
requirements. 
5. Created an Index on the AccountDetails table to enhance query performance. 
6. Designed an Entity-Relationship (E-R) Diagram to visualize and understand entity relationships within the 
payroll management system for any organization.


### List of Entities: 
- **Employee:** Stores all personal details of each employee, covering comprehensive information related to that individual.  

- **Salary:** Records both current and historical salary details of employees; helps managers and HR track salary grade changes and promotion dates.  

- **Department:** Maintains data about all departments within the company that an employee can belong to.  

- **Account Details:** Stores information about the bank accounts linked by employees for salary credit purposes.  

- **Attendance:** Captures data on employee attendance, including the total number of hours worked each week.  

- **Project:** Holds information on all projects the company is currently handling as well as upcoming projects.  

- **Education:** Tracks each employee's academic qualifications, including all degrees earned.  

- **Work Location:** Stores details about office locations, including city, state, and the number of employees assigned to each location.  

- **Leave:** Records the number of leaves an employee has taken or applied for within a month or a year.

More information and ER diagrams are available in the pdf uploaded.

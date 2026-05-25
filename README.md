1) Employee Management System (IESC)

This project is an Employee Management System designed for **International Employment Services (IESC)**.  
The system stores, manages, and retrieves employee information, supporting recruitment and job‑matching activities between employers and employees.  
It includes multiple tables, forms, validation rules, macros, and VBA automation to ensure accurate and efficient data handling.  
The system is built to support a large enterprise with international recruitment needs.  


2) System Overview
The system manages three main components:
- **Employers** – enterprises offering job positions  
- **Agents** – intermediaries connecting employers and employees  
- ** Employees** – individuals applying for job roles  


It supports employee registration, job compatibility checks, check‑in/check‑out tracking, and secure login functionality.

3) Key Features
- Employee registration with details such as experience, job title, and compatibility  
- Employer check‑in and check‑out system  
- Validation rules to prevent incorrect data entry (e.g., age limits)  
- Lookup fields for controlled data selection  
- Automated calculations (e.g., time differences × standard pay)  
- Login and registration forms using VBA  
- Forms with buttons for adding, saving, and navigating records  


4) Database Design
The system includes **10+ tables**, such as:
- Employee  
- Department  
- Enrolment  
- Employer  
- Payment Details  
- Training  
- Bank  
- Leave  
- KIN  


Normalization was applied up to **3rd Normal Form** for multiple tables to reduce redundancy and improve data integrity.  


An ER diagram was created to illustrate relationships between tables.

5) Testing Summary
A series of 11 tests were performed, including:
- Age validation rule  
- Lookup wizard functionality  
- Add new record button  
- Save button  
- Input mask for time  
- Automatic calculations  
- VBA check‑in/check‑out  
- Login button navigation  
- Macro‑based form navigation  
- Registration form using VBA  
- Auto‑opening main form on startup  


Most tests were successful, with only minor issues (e.g., negative time calculations when end time < start time).

6) Implementation
The system uses:
- Tables with appropriate data types (short text, integer, lookup wizard, hyperlink)  
- Forms with buttons (save, add, login, register, etc.)  
- Macros and VBA code for automation and security  
- Reports for printing useful information  


7) Evaluation
The system successfully stores, manages, and retrieves employee data using SQL queries for insert, update, delete, and search operations.  
Future improvements include:
- Web integration using PHP  
- Data encryption for sensitive information  
- Multi‑factor authentication  
- Graphical dashboards for performance and salary trends  


8) Conclusion
This project demonstrates the ability to design a complete automated system using:
- SQL queries  
- Macros and VBA  
- Data validation  
- Form creation  
- Reporting tools  

Further improvement is planned in coding and macro development.  


 


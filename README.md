
This is a Hospital Management System developed in ASP and VB. The system allows hospital staff to manage patients, doctors, employees, expenses, salaries, payments, laboratory reports, and drugs. The system is built using SQL Server as the database.

Database Tables:
1. employees: This table stores details of all hospital employees, including their ID, name, contact number, address, age, gender, job title, salary, skills, and registration date.
2. users: This table stores login credentials for staff members, including their ID, employee ID, username, password, and registration date.
3. expenses: This table stores details of all expenses incurred by the hospital, including the expense ID, name, amount, description, and registration date.
4. salary: This table stores information about the salary of each employee, including their ID, fee amount, amount paid, amount remaining, and registration date.
5. patients: This table stores information about all patients, including their ID, name, contact number, address, age, gender, fee, and registration date.
6. diseases: This table stores the name and registration date of all diseases.
7. patient_interview: This table stores the details of patient interviews, including the interview ID, patient ID, doctor ID, disease ID, and registration date.
8. payments: This table stores information about payments made by patients, including the payment ID, patient ID, fee paid, amount paid, amount remaining, and registration date.
9. laboratory: This table stores information about laboratory reports, including the report ID, patient ID, disease type, and registration date.
10. drugs: This table stores information about all drugs used in the hospital, including the drug ID, name, issue date, expire date, country, quantity, price, and registration date.

Requirements:
1. Visual Studio 2017 or later
2. Microsoft SQL Server Management Studio 2012 or later
3. .NET Framework 4.5 or later

Installation:
1. Clone or download the project files from GitHub.
2. Open the project solution in Visual Studio.
3. Open SQL Server Management Studio and create a new database named 'cs20i'.
4. Execute the SQL script 'DatabaseScript.sql' to create the necessary tables in the database.
5. In the project, open the 'Web.config' file and modify the connection string to match your SQL Server instance.
6. Build and run the project.


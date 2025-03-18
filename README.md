### Crud_mysql
![Show Employees](https://github.com/damiancodes/crud_mysqldjango/blob/master/employee/static/images/show.png)


### Adding an Employee
This section allows the admin to add new employee details.

![Add Employee](https://github.com/damiancodes/crud_mysqldjango/blob/master/employee/static/images/add.png))

### Viewing and Managing Employees
This section displays a list of added employees along with options to update or delete their details.

![Show Employees](https://github.com/damiancodes/crud_mysqldjango/blob/master/employee/static/images/show.png)


# MySQL CRUD Application

## Overview
This is a simple MySQL-based CRUD (Create, Read, Update, Delete) application that allows an admin to manage employee details. The application provides functionality to add, view, update, and delete employee records.

## Features
- **Add Employee**: Admin can add new employee details.
- **View Employees**: Display a list of employees with their details.
- **Update Employee**: Modify existing employee records.
- **Delete Employee**: Remove an employee from the database.


## Requirements
- MySQL Server
- PHP (if using PHP for backend processing)
- Web Server (e.g., Apache, Nginx) if running as a web application

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Import the database:
   - Open MySQL and create a database: `CREATE DATABASE employee_db;`
   - Import the provided SQL file: `mysql -u root -p employee_db < database.sql`
3. Configure database connection in your application:
   ```php
   $conn = new mysqli('localhost', 'root', '', 'employee_db');
   ```
4. Start your server and access the application.

## Usage
- Navigate to the **Add Employee** section to insert a new employee.
- View all employees in the **Show Employees** section.
- Use the edit and delete options to modify or remove employee records.

## Future Enhancements
- Implement user authentication.
- Add search and filter functionality.
- Improve UI design.

## License
This project is open-source. Feel free to modify and use it as needed.

## Author
damiancodes


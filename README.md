# Employee Management System

## Overview
The **Employee Management System** is a full-stack web application designed to manage employee records efficiently. It includes features for adding, updating, deleting, and viewing employee details. The system is built using:

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL

![Project Preview](EMPS.png)


## Features
- Employee Registration & Management
- User Authentication (Login/Logout)
- Role-Based Access Control (Admin & Employee)
- CRUD Operations (Create, Read, Update, Delete)
- Responsive UI

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Server:** Apache (XAMPP/LAMP)

## Installation
### Prerequisites
Ensure you have the following installed:
- XAMPP/LAMP for local development
- MySQL Database
- Web Browser

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/employee-management-system.git
   ```
2. Move the project to your server directory:
   ```sh
   mv employee-management-system /var/www/html/ # For Linux
   ```
   or
   ```sh
   C:\xampp\htdocs\employee-management-system # For Windows (XAMPP)
   ```
3. Import the database:
   - Open **phpMyAdmin**
   - Create a new database named `employee_db`
   - Import `employee_db.sql` file (provided in the repository)

4. Configure Database Connection:
   - Open `config.php`
   - Update the database credentials:
   ```php
   $servername = "localhost";
   $username = "root";
   $password = "";
   $dbname = "employee_db";
   ```
5. Start Apache & MySQL (XAMPP Control Panel)
6. Open the browser and navigate to:
   ```
   http://localhost/employee-management-system/
   ```

## Usage
- **Admin Panel:** Manage employees, assign roles, and monitor activities.
- **Employee Dashboard:** View personal details, update profile, and check tasks.


## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository
2. Create a new branch (`feature-branch`)
3. Commit your changes
4. Push to your fork and submit a Pull Request




# Employee Management System

This **Employee Management System** is a web application built with PHP for the frontend and MySQL as the database backend. It provides an interface for managing employee data, including features such as adding, updating, and deleting employee records, managing user roles, and tracking employee attendance.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Database Structure](#database-structure)
- [Future Enhancements](#future-enhancements)
- [License](#license)

## Introduction

Managing employee data is essential for every organization. This system enables administrators to efficiently manage employee records and monitor attendance. It also provides a user-friendly interface for employees and administrators to log in and manage their respective data.

## Features

- **Admin Login**: Manage employee records, view attendance, and handle user roles.
- **Employee Login**: View and update personal information.
- **CRUD Operations**: Add, update, delete, and view employee records.
- **Database Management**: Stores employee information, user roles, and login details.
- **Responsive Design**: Accessible on various devices.
  
## Installation

### Prerequisites

1. **XAMPP**: Download and install XAMPP for the Apache server and MySQL database.
2. **Text Editor**: Notepad++, Sublime Text, or any other preferred text editor.

### Steps

1. **Download the Project**:
   - Clone or download the `Employee_Management_System` project folder and extract it if downloaded as a zip file.
   
2. **Move the Project**:
   - Copy the `Employee_Management_System` folder and paste it into the `htdocs` directory within the XAMPP installation folder (usually found in `C:/xampp/htdocs`).
   
3. **Set Up the Database**:
   - Open XAMPP Control Panel and start the **Apache** and **MySQL** modules.
   - Go to [phpMyAdmin](http://localhost/phpmyadmin).
   - Create a new database named `ems`.
   - Import the `ems.sql` file located in the `SQL file` folder of the project directory.

4. **Run the Application**:
   - In your browser, go to [http://localhost/Employee_Management_System](http://localhost/Employee_Management_System) to access the system.
   

## Usage

- **Admin Panel**: Admin can log in to add, update, and delete employee records. The admin also has access to view all employee data and attendance records.
- **Employee Dashboard**: Employees can log in to view their personal details and manage their profile.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, PHP
- **Backend**: PHP, MySQL
- **Database**: MySQL
- **Server**: XAMPP (Apache and MySQL)

## Database Structure

The `ems` database includes tables for:
- **Employees**: Stores personal details of each employee.
- **Users**: Stores login credentials and user roles.
- **Attendance**: Tracks employee attendance.

## Future Enhancements

- **Advanced Reporting**: Generate detailed reports for employee attendance, performance, and other metrics.
- **Role-Based Access Control**: Enhance the current system to support various user roles with different permissions.
- **Notification System**: Implement notifications for important events, such as attendance anomalies or upcoming employee reviews.
- **Mobile-Friendly Design**: Improve the user interface for better mobile accessibility.


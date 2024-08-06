# courier-management-system
Courier Management System This is a simple PHP/MySQLi project to manage courier services. The system allows tracking of parcels, managing branches, staff, and users.

## Table of Contents
Features Tech Stack Installation Usage Contributing

## Features
User Registration and Login Parcel Tracking Branch Management Staff Management Parcel Management Reports Generation

## Tech Stack
Front-end: HTML, CSS, Bootstrap Back-end: PHP Database: MySQL

## Installation
Prerequisites PHP >= 7.0 MySQL >= 5.7 Web Server (e.g., Apache) XAMPP (Recommended for local development)

## Steps
Clone the Repository

## Set Up Local Server Environment
Install XAMPP or any similar local server environment that supports PHP and MySQL. Start the Apache and MySQL modules from the XAMPP control panel.

## Import the Database
Open phpMyAdmin from your browser (usually accessible at http://localhost/phpmyadmin). Create a new database (e.g., courier_db). Import the SQL file from the database directory of the repository:

## Copy code
CREATE DATABASE courier_db; USE courier_db; SOURCE path/to/database/schema.sql; Configure Database Connection

## Open dbconnection.php or the relevant configuration file in the project.
Update the database credentials to match your local setup: php Copy code $servername = "localhost"; $username = "root"; $password = ""; $dbname = "courier_db"; Run the Application

Move the project files to the htdocs directory of your XAMPP installation.
Access the application by navigating to http://localhost/courier_management_system in your web browser.

## Usage
Register as a new user or log in with existing credentials. Navigate through the dashboard to manage parcels, track shipments, and handle branch and staff information. Admin users have additional privileges to manage the entire system.

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests.

## Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature) Commit your Changes (git commit -m 'Add some AmazingFeature') Push to the Branch (git push origin feature/AmazingFeature) Open a Pull Request

# Enye-Assessment
Take-home programming assessment using PHP and MySQL with authentication and basic task management.


# Simple Task Management System (Enye Assessment)

A basic PHP/MySQL CRUD application featuring user authentication with password hashing and session management.

## Setup Instructions
1. Database Setup:
   - Create a database named `enye_db` in your MySQL server sa Xampp or Wampp.
   - Import the `database.sql` file provided in this folder.
2. Configuration:
   - Ensure `db.php` has the correct credentials (default).
3. How to Run:
   - Place the project folder in your web server's directory (`C:/wamp64/www/`).
   - Access the application via `http://localhost/Enye-Assessment/register.php`.

 Security Features Implemented
- Password Hashing**: Uses `password_hash()` with `PASSWORD_DEFAULT`.
- SQL Injection Prevention**: All queries use Prepared statements.
- Session Management: Secure login/logout using PHP sessions.

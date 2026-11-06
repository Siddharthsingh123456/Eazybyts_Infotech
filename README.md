# EazyByts Infotech — PHP Chat Application

A PHP and JavaScript chat application project with login/signup flows, user lookup, and message-related server endpoints backed by a SQL database.

## Features represented in the source
- Login and signup pages
- User listing and search
- Chat interface
- Client-side JavaScript for authentication and chat interactions
- PHP endpoints for signup, login, logout, user search, and message retrieval/insertion
- SQL schema file for the chat application

## Technology
- PHP
- MySQL/MariaDB
- JavaScript
- HTML and CSS

## Requirements
- PHP-enabled local server (XAMPP, WAMP, or equivalent)
- MySQL or MariaDB
- Browser
- phpMyAdmin or SQL client

## Local setup
1. Clone the repository into the web server document root.
2. Create a MySQL database for the application.
3. Inspect and import `chatapp.sql`.
4. Review `php/config.php` and set local database connection details.
5. Start Apache and MySQL.
6. Open the project through localhost.

The exact database name and credentials must match your local configuration; do not reuse production credentials.

## Important security review
Before deploying, verify that passwords are hashed securely, SQL uses prepared statements, sessions are protected, and all user-controlled input is validated. The repository contains `unzipper.php`; review whether it is needed and remove it from any public deployment if it is an unused file-extraction utility. Do not expose database credentials or real user data.

## License
No license file is currently specified. Contact the repository owner before reuse.

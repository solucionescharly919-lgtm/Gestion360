# Gestion360

**Gestion360** is a comprehensive management system designed to help organizations streamline operations, monitor tasks, and manage users efficiently. Built with **PHP**, **MySQL**, and **Bootstrap 5**, it provides a secure and user-friendly interface for daily administrative activities.

---

## Features

- Multi-level user roles and permissions (Admin, User, Observer)
- Task and activity tracking with observation logs
- Module management for flexible expansion
- File and folder management with access control
- Reports and exports in Excel format
- Security features:
  - Forced password change for temporary passwords
  - Lockout after failed login attempts
  - Session expiration due to inactivity
  - Activity logs
  - IP alerts for suspicious activity
  - Two-factor authentication (2FA)
  - Password recovery via token

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/gestion360.git
2. Navigate to the project folder: cd gestion360
3. Configure your database connection in: /config/config.php
4. Import the database schema using the provided SQL files.
5. Open the project in your web server (e.g., Apache or Nginx).
Usage
1. Access the login page at: http://your-domain.com/login.php
2. Log in with your credentials.
3. Navigate through the dashboard to manage tasks, modules, users, and reports.
4. Use the administrative panel for advanced configurations.


Contributing

Contributions are welcome! Please fork the repository and submit a pull request. Make sure to follow the Apache License 2.0 guidelines.

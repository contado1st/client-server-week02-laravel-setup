# ITST 302 — Professional Laravel Development Environment Setup

## 1. Project Title

**Hello Laravel — Client-Server Development Environment Setup**

**Subject:** ITST 302 — Client-Server Technologies  
**Project:** Mini Project 01: Professional Laravel Development Environment  
**Course:** Bachelor of Science in Information Technology (BSIT)  

---

## 2. Introduction

### Overview of Laravel
Laravel is a robust, open-source framework built for PHP that simplifies backend web development through modern architectural patterns. By leveraging the Model-View-Controller (MVC) design pattern, it abstracts complex low-level operations such as request routing, database connectivity, and dynamic page rendering into intuitive, readable components. This allows developers to build maintainable, full-stack web applications without reinventing core infrastructure.

### Importance of Client-Server Technologies
Modern web applications rely on client-server architecture to separate user interaction from backend logic. In this model, the client interface (the web browser) submits requests over a network, while the backend server processes business logic, executes database operations, and delivers the appropriate response back to the client. Gaining hands-on experience with configuring local web runtimes and database servers provides essential insight into how distributed software systems operate in real-world deployments.

### Purpose of the Project
Developed as part of the ITST 302 Client-Server Technologies curriculum, this activity focuses on establishing and validating a complete local backend environment. The objective is to assemble a working development stack consisting of PHP, Composer, the Laravel CLI, MySQL, and Git. The workflow involves initializing a fresh Laravel instance, launching the Artisan development server, modifying Blade views to serve customized student information, and tracking all setup stages across a public Git repository.

---

## 3. Objectives

The following learning objectives were achieved upon completion of this activity:

1. Installed and configured PHP 8.4.21 as the core server-side scripting environment.
2. Verified Composer 2.9.5 as the global dependency manager for PHP packages.
3. Installed and verified the Laravel CLI installer globally.
4. Installed, configured, and verified MySQL Server 8.0.45 for database management.
5. Configured Git 2.54.0 version control and established proper commit conventions.
6. Initialized and opened the project inside Visual Studio Code v1.132.0 as the primary IDE.
7. Generated a clean Laravel project (`client-server-week02-laravel-setup`) using Composer.
8. Initiated the application locally using the `php artisan serve` development server.
9. Customized the default Blade view (`welcome.blade.php`) with dynamic metadata and styling.
10. Maintained structured version control with a minimum of 5 meaningful Git commits.

---

## 4. Development Environment

The local setup was built and verified using the following technologies:

| Tool / Component | Version |
| :--- | :--- |
| Operating System | Windows 11 |
| PHP | 8.4.21 |
| Laravel Installer | 5.25.1 |
| Composer | 2.9.5 |
| Git | 2.54.0.windows.1 |
| MySQL | 8.0.45 |
| Visual Studio Code | 1.132.0 |

### PHP Environment
PHP 8.4.21 serves as the server-side runtime for executing backend logic, running CLI tasks, and processing Artisan commands.

### Composer
Composer 2.9.5 serves as the dependency manager, managing global PHP binaries and project package installations.

### Laravel
The application utilizes Laravel Framework (initialized via Laravel Installer 5.25.1) to route incoming requests and serve dynamic Blade views.

### Git & GitHub
Git 2.54.0.windows.1 was configured for version control to track project iterations and publish the repository publicly to GitHub.

### MySQL Database
MySQL Community Server 8.0.45 was configured alongside system PATH variables to provide relational database capabilities.
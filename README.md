# ITST 302 — Professional Laravel Development Environment Setup

## 1. Project Title

**Hello Laravel — Client-Server Development Environment Setup**

**Subject:** ITST 302 — Client-Server Technologies  
**Project:** Mini Project 01: Professional Laravel Development Environment  
**Course:** Bachelor of Science in Information Technology (BSIT)  

---

## 2. Introduction

### Overview of Laravel
Laravel is an open-source PHP framework designed to streamline web development by using the Model-View-Controller (MVC) pattern. It handles complex backend operations—such as URL routing, database connections, and dynamic Blade template rendering—with clear, readable code. This framework allows developers to build maintainable, full-stack applications efficiently without building core server infrastructure from scratch.

### Importance of Client-Server Technologies
Client-server architecture is essential to modern web applications because it separates user interface components from backend processing logic. In this setup, the client browser issues HTTP requests over a network, and the server processes the request, manages database entries, and sends back the appropriate web view. Setting up a local web server and database environment provides practical experience with the mechanics of distributed software systems used in professional settings.

### Purpose of the Project
Prepared as part of the ITST 302 Client-Server Technologies course, this setup activity focuses on building and verifying a complete local development environment for the client-server-week02-laravel-setup project. The main goal is to assemble a functional stack including PHP 8.4, Composer, the global Laravel CLI, MySQL, and Git. The overall workflow involves initializing a new Laravel project, hosting it on the local Artisan server, updating resources/views/welcome.blade.php to present customized student information, and documenting each stage across a public GitHub repository.

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

---

## 5. Installation & Verification Steps

### Step 1 — Verify PHP Version
The PHP CLI runtime was verified in PowerShell:

```powershell
php -v
```

This confirmed that PHP 8.4.21 was active and properly recognized in the system terminal.

![PHP Version](screenshots/php-version.jpg)  
*Figure 1. Verification of PHP 8.4.21 installation.*

---

### Step 2 — Verify Composer Installation
Composer was verified using:

```PowerShell
composer -v
```

This output confirmed Composer version 2.9.5 was operating on top of the PHP runtime.

![Composer Version](screenshots/composer-version.jpg)  
*Figure 2. Verification of Composer dependency manager.*

---

### Step 3 — Verify Laravel Installer
The global Laravel CLI tool was verified using:

```powershell
laravel -V
```

This confirmed Laravel Installer 5.27.0 was installed and ready to scaffold new applications.

![Laravel Version](screenshots/laravel-version.jpg)  
*Figure 3. Verification of global Laravel CLI.*

---

### Step 4 — Verify Git Version Control
Git installation and system identity were verified using:

```powershell
git --version
```

![Git Version](screenshots/git-version.jpg)  
*Figure 4. Verification of Git version control system.*

---

### Step 5 — Verify MySQL Server
MySQL binary availability was verified in the terminal using:

```powershell
mysql --version
```

This confirmed MySQL Community Server 8.0.44 was properly bound to the system PATH.

![MySQL Version](screenshots/mysql-version.jpg)  
*Figure 5. Verification of MySQL database server.*

---

### Step 6 — Verify Visual Studio Code Setup
The project folder was opened in Visual Studio Code to verify workspace configurations and workspace extensions.

![VS Code Setup](screenshots/vscode.jpg)  
*Figure 6. Workspace structure opened inside VS Code.*

---

### Step 7 — Create the Laravel Project
A fresh Laravel project named `hello-laravel` was initialized using Composer:

```PowerShell
composer create-project laravel/laravel contado-week2-laravel-setup
```

---

### Step 8 — Start Development Server
The local server was started using Artisan:

```powershell
php artisan serve
```

The application started listening on `http://127.0.0.1:8000`.

![Artisan Serve](screenshots/run-laravel.php-artisan-serve.jpg)  
*Figure 7. Laravel Artisan development server running.*

---

### Step 9 — Customize Application Homepage
The landing page was customized by modifying `resources/views/welcome.blade.php`. Custom CSS and dynamic Carbon date formatting were included to present student metadata cleanly.

![Custom Homepage](screenshots/homepage.png)  
*Figure 8. Customized Laravel application landing page.*
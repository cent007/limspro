# LIMSPro - Library Information Management System

LIMSPro is a web-based Library Information Management System designed to modernize and automate traditional library processes. It features real-time inventory tracking, advanced catalog search, automated check-in/check-out, fines management, and powerful reporting tools. Built with PHP, MySQL, HTML, CSS, JavaScript, jQuery, and Bootstrap, LIMSPro delivers a robust and scalable library experience for both staff and patrons.

## Installation Guide

### Prerequisites
Ensure you have the following installed on your system:

- XAMPP (for Apache and MySQL)
- Git
- Visual Studio Code (VS Code)

### 1. Clone the Repository

- Copy this repository link: `https://github.com/cent007/limspro`
- Create a folder named `limspro` inside the `htdocs` directory in your XAMPP installation.
- Open the `limspro` folder in Visual Studio Code.
- Open a new terminal in VS Code and run the following command:

  ```bash
  git clone https://github.com/cent007/limspro .
  ```

**Note:** Ensure there is a space and a dot (.) at the end of the command to clone the repository directly into the current directory.

### 2. Database Setup

- Start XAMPP.
- Open phpMyAdmin and create a new database named `limspro`.
- Locate the `SQL_SCRIPTS` folder in the root directory of the project.
- Import the `limspro.sql` schema file into the newly created database.

### 3. Start the Application

- Ensure Apache and MySQL services are running in XAMPP.
- Open a web browser and navigate to:

  ```
  http://localhost/limspro
  ```

- The LIMSPro - Library Information Management System should now be up and running on your local server.

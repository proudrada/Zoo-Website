# 🦁 Zoo Website Management System

![Language](https://img.shields.io/badge/language-PHP-777BB4.svg)
![Database](https://img.shields.io/badge/database-MySQL-4479A1.svg)
![Frontend](https://img.shields.io/badge/frontend-HTML%20%2F%20CSS-orange.svg)

A web-based management application designed to help zookeepers and administrators efficiently oversee daily zoo operations, track animal data, manage designated zones, and handle dietary logistics.

## User Roles & Features

### Zookeepers
* **Profile Management:** View and manage personal zookeeper profile details.
* **Animal & Zone Tracking:** View assigned animals and specific zoo zones/habitats.
* **Dietary Logistics:** Manage ingredients and plan meals for the animals under their care.

### Administrators
* **Full Control:** Access to a complete administrative dashboard.
* **Staff Management:** Oversee, add, update, or remove Zookeeper accounts.
* **Zoo Logistics:** Full CRUD (Create, Read, Update, Delete) capabilities over **Animals**, **Zones**, and **Meals**.

## Tech Stack
* **Backend:** PHP
* **Database:** MySQL
* **Frontend:** HTML, CSS

## Getting Started

Follow these instructions to get the project up and running on your local machine using a local server environment like XAMPP, WAMP, or MAMP.

### Prerequisites
* A local web server environment (e.g., **XAMPP** version 7.4 or higher)
* Web browser (Chrome, Firefox, Edge, etc.)

### Installation & Setup

1. **Clone the repository:**
   Move into your local server's root directory (e.g., `xampp/htdocs/`) and clone the project:
   ```bash
   cd /path/to/xampp/htdocs
   git clone [https://github.com/proudrada/Zoo-Website.git](https://github.com/proudrada/Zoo-Website.git)
   
2. **Database Setup:**
   * Open your browser and navigate to http://localhost/phpmyadmin.
   * Create a new database named zoo_management (or your preferred name).
   * Click on the Import tab.
   * Choose the .sql file included in this repository (e.g., database.sql or zoo.sql) and click Go to import the tables and sample data.
    
3. **Configure Database Connection:**
   * Open the project folder in your text editor.
   * Locate the database configuration file (usually config.php, db.php, or connection.php).
   * Update the credentials to match your local server environment

4. **Run the Application:**
   * Open your web browser and go to:
     ```bash
     (http://localhost/Zoo-Website)

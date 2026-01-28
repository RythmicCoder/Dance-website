# Dance Website

Dance Website is a full-stack dance academy web application developed to showcase dance forms, team members, gallery shots, and to provide user authentication with real database connectivity.

This project represents hands-on implementation of frontend development, backend logic, REST APIs, and database integration using modern web technologies.

---

## Table of Contents

- Project Overview  
- Features  
- Tech Stack  
- System Architecture  
- Project Structure  
- Database Design  
- REST API Implementation  
- Installation & Setup  
- Running the Project  
- Screenshots  
- Learning Outcomes  
- Future Improvements  
- Author  
- License  

---

## Project Overview

The Nadans Website was built as a practical full-stack web development project. It focuses on combining user-friendly UI design with secure backend functionality and structured database management.

The platform allows users to:

- Explore different dance forms  
- View dance galleries and team members  
- Register and log in securely  
- Interact with dynamic data fetched from the database using REST APIs  

This project reflects real-world website architecture used in production systems.

---

## Features

### Frontend
- Fully responsive layout  
- Multi-page navigation system  
- Modern UI design  
- Gallery and content sections  
- Interactive components using JavaScript  

### Backend
- User authentication system  
- Secure database connectivity  
- REST API endpoints  
- Server-side validation  

### Database
- Structured relational database  
- SQL queries for data storage and retrieval  
- phpMyAdmin integration  

---

## Tech Stack

### Frontend Technologies
- HTML
- CSS
- JavaScript  

### Backend Technologies
- PHP  
- Node.js  

### Database
- MySQL  
- phpMyAdmin  

### Tools & Platforms
- Visual Studio Code  
- XAMPP / WAMP  
- Git & GitHub  

---

## System Architecture
User Browser
|
Frontend (HTML, CSS, JS)
|
REST API (PHP)
|
Database (MySQL)

The frontend communicates with backend REST APIs, which handle authentication and data operations and interact with the MySQL database.

---

## P
---

## Database Design

The database includes tables such as:

- users  
- dance_forms  
- gallery  
- contact_messages  

### Sample Fields

**users**
- id  
- name  
- email  
- password  

**dance_forms**
- id  
- name  
- description  
- image_path  

---

## REST API Implementation

The project uses PHP-based REST APIs for:

- User authentication  
- Fetching dance form data  
- Loading gallery content dynamically  
- Handling form submissions  

Example endpoints:

/php/api/getDanceForms.php
/php/api/getGallery.php

These APIs return JSON responses and connect directly to the MySQL database.

---

## Installation & Setup

### Prerequisites

- XAMPP or WAMP installed  
- PHP 7+  
- MySQL  
- Web browser  

---

## Database Setup

1. Open **phpMyAdmin**
2. Create a database named:






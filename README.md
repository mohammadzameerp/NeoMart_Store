# NeoMart Store
E-Commerce Website

## Overview

This project is a full-stack e-commerce website using React for the frontend, Spring Boot for the backend, and MySQL as the database. The application allows users to browse products, add them to the cart, and make purchases. Admins can manage the product inventory through CRUD operations.

## Features🪶

- Product listing and details
- Shopping cart functionality
- Order management
- Admin panel for product management
- Responsive design
- Add, update, delete, and create products with images

## Technologies Used 

<a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a>
+
<a href="https://spring.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> </a>
+
<a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> 
+
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> 
+
<a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a>

### Frontend 🤖

- React
- Axios
- React Router

### Backend

- Spring Boot
- Spring Data JPA
- MySQL

## Prerequisites

- Node.js and npm
- Java 8 or higher
- Maven 3.6 or higher
- MySQL

## Project Structure

### Backend
```bash
backend
├── src
│ ├── main
│ │ ├── java
│ │ │ └── com
│ │ │ └── NeoMart
│ │ │ └── ecom_proj
│ │ │ ├── controller
│ │ │ │ └── ProductController.java
│ │ │ ├── model
│ │ │ │ └── Product.java
│ │ │ ├── repository
│ │ │ │ └── ProductRepository.java
│ │ │ ├── service
│ │ │ │ └── ProductService.java
│ │ │ └── EcommerceApplication.java
│ ├── resources
│ │ ├── application.properties
│ │ └── schema.sql
│ └── test
│ └── java
│ └── com
│ └── ravi
│ └── ecom_proj
│ └── EcommerceApplicationTests.java
├── pom.xml
└── ...
```

# Employee Management System

## Overview
This is a Spring Boot application that provides a simple Employee Management System. It allows you to perform CRUD (Create, Read, Update, Delete) operations on employee data.

## Features
- Add new employees
- Update existing employee details
- Fetch employee details using their Employee ID
- Delete employees

## Technologies Used
- Spring Boot
- MySQL
- REST API

## Getting Started

### Prerequisites
- Java 8 or higher
- MySQL


## API Endpoints
- `POST /employees`: Add a new employee
- `PUT /employees/{id}`: Update an existing employee
- `GET /employees/{id}`: Fetch an employee using their ID
- `DELETE /employees/{id}`: Delete an employee


### Installation
1. Clone the repository
  git clone https://github.com/ayush-aks29/Spring-Boot-CRUD-app.git

3. Navigate to the project directory
  cd Spring-Boot-CRUD-app

5. Build the project
./mvnw clean install

7. Run the application
./mvnw spring-boot:run


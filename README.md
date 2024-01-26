# SpringBoot-student-API

This repository contains a simple CRUD (Create, Read, Update, Delete) operation implemented in SpringBoot.

## Overview

The project demonstrates the implementation of a RESTful API using SpringBoot framework to perform CRUD operations on a simple "Students" table in the database.

## Features 

- Exposes REST API endpoints for:
  - Select/GET (Retrieve all students or a specific student)
  - Insert/POST (Add a new student)
  - Update/POST (Update an existing student)
  - Delete/DELETE (Delete a student)
- Utilizes Spring Data JPA for database operations
- Follows best practices for RESTful API design and SpringBoot development

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- Maven

## Getting Started

To run this application locally, follow these steps:

1. Clone this repository: gitHub : https://github.com/akash-dalvi22/SpringBoot-student-API.git
 
2. Navigate to the project directory:


3. Build the project using Maven:


4. Run the application:


5. The application will start, and you can access the API endpoints.

## API Endpoints

- GET /api/students: Retrieve all students
- GET /api/students/{id}: Retrieve a specific student by ID
- POST /api/create: Add a new student
- POST /api/students/{id}: Update an existing student by ID
- DELETE /api/delete/{id}: Delete a student by ID

## Technologies Used

- SpringBoot
- Spring Data JPA
- MySql Database
- Maven

## Contributing 

Contributions are welcome! Please fork this repository and create a pull request with your changes.







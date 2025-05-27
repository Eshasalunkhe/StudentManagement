# Student Management System - REST API

This project is a simple **Student Management REST API** built using **Spring Boot**. It allows you to perform basic CRUD (Create, Read, Update, Delete) operations on student data.

## Features

- Add a new student
  ![post](https://github.com/user-attachments/assets/8a599b70-471d-4a8a-a8e0-2d6de13a27aa)

- Get all students
- ![get](https://github.com/user-attachments/assets/c3f1d0b1-9779-4999-90a1-cf1db6fe0a75)

- Get a student by ID

![getbyid](https://github.com/user-attachments/assets/fb7cb181-3da8-4d15-aff9-78bf8e4f9196)

- Update student details

- ![update](https://github.com/user-attachments/assets/bb364a1c-1009-48d0-ab10-bf7e6b34a79d)

- Delete a student

- ![delete](https://github.com/user-attachments/assets/2468c084-7ea4-4815-92ed-f0bfb2b6296a)


## Tech Stack

- Java
- Spring Boot
- Spring Web
- Spring Data JPA (if you're using a database)
- H2 Database or MySQL (optional)
- Postman (for API testing)

## API Endpoints

| Method | Endpoint           | Description              |
|--------|--------------------|--------------------------|
| POST   | `/students`        | Add a new student        |
| GET    | `/students`        | Get all students         |
| GET    | `/students/{id}`   | Get a student by ID      |
| PUT    | `/students/{id}`   | Update a student         |
| DELETE | `/students/{id}`   | Delete a student         |



# TodoApp-intermediate-version

Level 1 (Beginner)

Ye projects CRUD + JPA + REST API practice ke liye hain.

1. Todo App

Features:

Create Task
Update Task
Delete Task
Mark Complete
Search Tasks

Skills:

Spring Boot
JPA
PostgreSQL/MySQL
REST APIs


Todo App Features
Basic Version

✅ Create Todo
✅ Get All Todos
✅ Get Todo By ID
✅ Update Todo
✅ Delete Todo


Intermediate Version

✅ Validation
✅ Exception Handling
✅ DTO
✅ Pagination
✅ Sorting


Advanced Version

✅ Spring Security + JWT
✅ User-wise Todos

Project Structure
src/main/java

com.todo

├── controller
│     └── TodoController
│
├── service
│     ├── TodoService
│     └── TodoServiceImpl
│
├── repository
│     └── TodoRepository
│
├── entity
│     └── Todo
│
├── dto
│     ├── TodoRequest
│     └── TodoResponse
│
├── exception
│     ├── ResourceNotFoundException
│     └── GlobalExceptionHandler
│
└── TodoApplication

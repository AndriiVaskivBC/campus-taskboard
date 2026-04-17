# Campus Task Board API

## 📌 Project Description
This project is a Spring Boot REST API that allows users to manage tasks.  
It supports full CRUD operations (Create, Read, Update, Delete) and includes validation for input data.

The API was developed using Java and Spring Boot and tested using Postman.

---

## ✨ Features
- Create tasks
- View all tasks
- Get task by ID
- Update tasks
- Delete tasks
- Input validation

---

## ⚙️ How to Run the Application

### Requirements:
- Java 17 or 21
- Maven (or use included mvnw wrapper)

### Steps:

1. Clone the repository:
```bash
git clone https://github.com/AndriiVaskivBC/campus-taskboard.git
```

2. Navigate to the project folder
cd campus-taskboard

3. Run the application:
On Windows:
mvnw.cmd spring-boot:run

On Mac/Linux:
./mvnw spring-boot:run


4. Open in browser:
http://localhost:8080/api/tasks

### 🌐 API Endpoints
GET all tasks
```bash
GET /api/tasks
```
GET task by ID
```bash
GET /api/tasks/{id}
```
POST create task
```bash
POST /api/tasks
```
POST /api/tasks
```bash
PUT /api/tasks/{id}
```
DELETE task
```bash
DELETE /api/tasks/{id}
```

### 📸 API Testing
All endpoints were tested using Postman:
- GET all tasks
- POST create task
- GET by ID
- PUT update
- DELETE
- Validation error
Screenshots are included in the submission.

### 🎥 Video Demo
link

# To-Do Manager REST API

A simple RESTful API built with *Spring Boot* and *MySQL* to manage daily tasks. This project allows users to create, read, update, and delete (CRUD) their to-do items.

## Features

- Create a new task
- Retrieve all tasks
- Update an existing task
- Delete a task
- Connects to MySQL using Spring Data JPA
- Follows layered architecture (Controller, Service, Repository)
- Uses standard HTTP methods and status codes

## Technologies Used

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- MySQL
- Maven

## API Endpoints

## API Endpoints

| Method | Endpoint           | Description             |
|--------|--------------------|-------------------------|
| GET    | /api/todos       | Get all tasks           |
| GET    | /api/todos/{id}  | Get a task by ID        |
| POST   | /api/todos       | Create a new task       |
| PUT    | /api/todos/{id}  | Update an existing task |
| DELETE | /api/todos/{id}  | Delete a task           |

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git ,cd YOUR-REPO-NAME
````
 ## 2. Configure the Database

Update your application.properties:
spring.datasource.url=jdbc:mysql://localhost:3306/todo_db
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
spring.jpa.hibernate.ddl-auto=update

## 3. Run the Application
`./mvnw spring-boot:run
or
mvn spring-boot:run`

![Screenshot (102)](https://github.com/user-attachments/assets/fa8e2358-1951-42e1-a10d-32a3be33d80c)
![Screenshot (101)](https://github.com/user-attachments/assets/725d0b18-f36b-4fae-b334-423077a7348a)
![Screenshot (100)](https://github.com/user-attachments/assets/974f217a-ae26-4d6b-8649-a35744f43f01)
![Screenshot (97)](https://github.com/user-attachments/assets/b9e48a25-7b0f-4a00-80e9-499c72f301e3)
![Screenshot (94)](https://github.com/user-attachments/assets/68f895af-470d-4ddd-b90b-a0095a6de8db)
![Screenshot (85)](https://github.com/user-attachments/assets/2921606b-1b39-4838-a0ce-45ad52507889)


License
This project is licensed under the MIT License.

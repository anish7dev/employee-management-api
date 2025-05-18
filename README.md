# Employee Management API

A simple Spring Boot CRUD REST API to manage employees.

## Tech Stack
- Java 17
- Spring Boot
- Spring Data JPA
- H2 Database

## API Endpoints

| Method | Endpoint        | Description        |
|--------|------------------|--------------------|
| GET    | /employees       | Get all employees  |
| POST   | /employees       | Add new employee   |
| PUT    | /employees/{id}  | Update employee    |
| DELETE | /employees/{id}  | Delete employee    |

## How to Run

```bash
./mvnw spring-boot:run
```

Access the app at: http://localhost:8080  
H2 Console: http://localhost:8080/h2-console

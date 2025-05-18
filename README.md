# Employee Management API 🧑‍💼

![GitHub repo size](https://img.shields.io/github/repo-size/anish7dev/employee-management-api)
![GitHub last commit](https://img.shields.io/github/last-commit/anish7dev/employee-management-api)
![GitHub language count](https://img.shields.io/github/languages/count/anish7dev/employee-management-api)
![GitHub issues](https://img.shields.io/github/issues/anish7dev/employee-management-api)

A Spring Boot-based CRUD REST API for managing employees. This backend service demonstrates clean architecture, RESTful principles, and uses Spring Data JPA with an H2 in-memory database.

---

## 🔧 Tech Stack

- Java 17
- Spring Boot 3.2
- Spring Data JPA
- H2 Database
- Maven

---

## 📁 Project Structure

src/
└── main/
└── java/com/example/employee/
├── controller/ # REST API endpoints
├── model/ # Employee entity
├── repository/ # JPA repository
└── EmployeeManagementApiApplication.java


---

## 📮 API Endpoints

| Method | Endpoint              | Description           |
|--------|-----------------------|-----------------------|
| GET    | `/api/employees`      | Get all employees      |
| GET    | `/api/employees/{id}` | Get employee by ID     |
| POST   | `/api/employees`      | Add a new employee     |
| PUT    | `/api/employees/{id}` | Update employee        |
| DELETE | `/api/employees/{id}` | Delete employee        |

---

## 🚀 Getting Started

### Run Locally

```bash
git clone https://github.com/anish7dev/employee-management-api.git
cd employee-management-api
mvn spring-boot:run

Then open: http://localhost:8080/api/employees

Example Payload (POST)
{
  "name": "John Doe",
  "email": "john.doe@example.com",
  "jobTitle": "Backend Developer"
}

🗂️ Database
This app uses an in-memory H2 database, accessible at:

URL: http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:testdb

Username: sa

Password: (leave blank)

👨‍💻 Author
Anish Choudhary – Java Backend Developer

GitHub

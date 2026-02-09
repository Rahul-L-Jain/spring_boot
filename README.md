# Employee Management System

A Spring Boot application for managing employee records. This application provides RESTful APIs to perform CRUD (Create, Read, Update, Delete) operations on employee data.

## 🚀 Technologies Used
- **Java** (JDK 17+)
- **Spring Boot** (Web, Data JPA)
- **H2 Database** (In-memory database)
- **Maven** (Build tool)

## 🛠️ Getting Started

### Prerequisites
- Java Development Kit (JDK) installed
- Maven installed (or use the included wrapper)

### Installation & Running
1. Clone the repository:
   ```bash
   git clone https://github.com/Rahul-L-Jain/spring_boot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd spring_boot
   ```
3. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

The application will start on `http://localhost:8080`.

## 📡 API Endpoints

### 1. Create a New Employee
- **URL:** `/employees`
- **Method:** `POST`
- **Body:**
  ```json
  {
    "name": "Jane Doe",
    "email": "jane@example.com",
    "department": "Engineering"
  }
  ```

### 2. Get All Employees
- **URL:** `/employees`
- **Method:** `GET`

### 3. Get Employee by ID
- **URL:** `/employees/{id}`
- **Method:** `GET`

### 4. Update Employee
- **URL:** `/employees/{id}`
- **Method:** `PUT`
- **Body:**
  ```json
  {
    "name": "Jane Smith",
    "email": "jane.smith@example.com",
    "department": "Marketing"
  }
  ```

### 5. Delete Employee
- **URL:** `/employees/{id}`
- **Method:** `DELETE`

- **User Name:** `sa`
- **Password:** *(Leave empty)*

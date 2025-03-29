# Spring Boot REST API  

## Introduction  
This project is a simple Spring Boot REST API for managing student data with multiple retrieval endpoints.  

## Requirements  
- Java 8+  
- Spring Boot  
- Maven/Gradle  

## API Endpoints  

### General  
- **`GET /app/msg`** – Returns a welcome message  
- **`GET /app/age/{age}`** – Returns a message with the given age  

### Student Operations  
- **`GET /app/student`** – Retrieves a single student  
- **`GET /app/students`** – Retrieves all students  
- **`GET /app/students/{regNo}`** – Finds a student by registration number  
- **`GET /app/ages`** – Retrieves students aged 20-23  
- **`GET /app/students/gpa`** – Retrieves students sorted by GPA  

## Student Data Model  
- **Registration Number (`regNo`)** – String  
- **Name (`name`)** – String  
- **Age (`age`)** – Integer  
- **Course (`course`)** – String  
- **GPA (`gpa`)** – Double  

## How to Run  
1. Clone the repository  
2. Build with **Maven/Gradle**  
3. Run the Spring Boot application  
4. Access endpoints via `http://localhost:8080/app/...`  

## Future Enhancements  
- Add database integration  
- Implement request validation and error handling  
- Introduce POST, PUT, DELETE operations  
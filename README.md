# Book Store

## Overview
The **Book Store** is a web application built using **Spring Boot, Thymeleaf, MySQL, and JPA**. It allows users to browse, search, and manage books efficiently.

## Features
- User authentication (Login/Registration)
- Add, update, and delete books
- Search books by title, author, or category
- View book details


## Technologies Used
- **Spring Boot** - Backend framework
- **Thymeleaf** - Template engine for dynamic UI rendering
- **Spring Data JPA** - ORM for database interaction
- **MySQL** - Relational database

- **Bootstrap** - Frontend styling

## Installation & Setup
### Prerequisites:
- Java 8 or later
- Maven
- MySQL Server
- IDE (IntelliJ IDEA, Eclipse, VS Code)

### Steps:
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/bookstore.git
   cd bookstore
   ```
2. **Configure Database:**
   - Update `application.properties` with your MySQL credentials:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/bookstore
     spring.datasource.username=root
     spring.datasource.password=root
     spring.jpa.hibernate.ddl-auto=update
     ```
3. **Build & Run the project:**
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```
4. **Access the application:**
   - Open `http://localhost:8080` in a browser.

## API Endpoints
| Endpoint           | Method | Description          |
|-------------------|--------|----------------------|
| `/`               | GET    | Home page           |
| `/books`          | GET    | List all books      |
| `/books/{id}`     | GET    | View book details   |
| `/books/add`      | POST   | Add a new book      |
| `/books/edit/{id}`| PUT    | Edit book details   |
| `/books/delete/{id}` | DELETE | Remove a book  |

#

## Contributing
Feel free to fork and contribute by submitting a pull request.


---
**Author:** Rohan Vishwakarma


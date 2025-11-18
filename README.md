Expense Tracker Application

A secure, user-friendly, and full-stack Expense Tracker Application built using Spring Boot, Spring Security, React.js, and MySQL. This project helps users manage their daily expenses with features like authentication, CRUD operations, and category-wise visual insights.

🚀 Features

🔐 Authentication & Security

Implemented Spring Security (Basic Authentication) for secure login.

Access control to ensure only authorized users can manage their expenses.


🗂 Expense Management (CRUD)

Add, View, Edit, and Delete expenses.

Each expense includes category, amount, comments, and timestamps.

Built using Spring M VC architecture (Controller → Service → Repository).


🌐 RESTful API Development

Designed and tested all APIs using Postman.

Proper request/response validation, HTTP status codes, and exception handling.


💻 Frontend (React.js)

Developed responsive and interactive UI using React.

Users can easily add, edit, or delete expenses.

Integrated Pie Chart visualization for category-wise expense distribution.


🧪 Unit Testing

Tested service layer logic using JUnit to ensure correctness and maintainability.

🛠 Tech Stack

Backend: Spring Boot, Spring Security (Basic Auth), Spring Data JPA
Frontend: React.js
Database: MySQL
Testing: Postman, JUnit
Architecture: MVC Pattern

📌 Project Architecture

Controller → Service → Repository → Database (MySQL)

Clear separation of concerns for clean, modular, and testable code.


📷 Screenshots (Add your images)

Dashboard

Add Expense Page

Pie Chart Visualization
---

📬 API Endpoints (Sample)

Expense APIs

Method	Endpoint	Description

GET	/api/expenses	Get all expenses
POST	/api/expenses	Add new expense
PUT	/api/expenses/{id}	Update existing expense
DELETE	/api/expenses/{id}	Delete expense
---

⚙ How to Run

Backend

1. Clone the repository
2. Configure application.properties (MySQL credentials)
3. Run the Spring Boot application

Frontend

1. Navigate to React project folder
2. Run: npm install
3. Start server: npm start

-------------------------------------

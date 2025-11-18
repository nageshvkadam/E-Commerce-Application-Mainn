E-Commerce Application

A full-stack, scalable, and high-performance E-Commerce Application developed using Spring Boot, React.js, and MySQL. This project includes complete backend architecture, REST APIs, frontend UI, routing, and cart/order workflows.
---

🚀 Features

🖥 Backend (Spring Boot)

Developed and maintained a high-performance and resilient backend using Spring Boot.

Followed MVC architecture (Controller → Service → Repository) for clean and modular development.

Implemented core e-commerce features:

User Management

Product Management

Cart Functionality

Order Processing


Designed and validated RESTful APIs using Postman for:

HTTP status codes

Payload structure

Error handling and exceptions

🔐 Security

Integrated Spring Security (Basic Authentication) to secure endpoints.

💻 Frontend (React.js)

Developed a dynamic and responsive UI for smooth user experience.

Used React Router for client-side routing across major pages:

Home

Products

Cart

Checkout

User Dashboard


Used React Hooks (useState, useEffect, useContext) for:

State management

Data fetching

Handling interactive UI events



🧪 Testing

Tested backend logic using JUnit to ensure proper functionality and maintainability.

Validated APIs thoroughly using Postman.



---

🛠 Tech Stack

Backend: Spring Boot, Spring Security (Basic Auth), Spring Data JPA
Frontend: React.js, React Router, React Hooks
Database: MySQL
Testing: Postman, JUnit
Architecture: MVC Pattern


---

📌 Project Architecture

Controller → Service → Repository → Database (MySQL)
React Frontend → REST APIs → Spring Boot Backend


---

📬 API Endpoints (Sample)

User APIs

Method	Endpoint	Description

POST	/api/users/register	User registration
POST	/api/users/login	User login


Product APIs

Method	Endpoint	Description

GET	/api/products	Get all products
GET	/api/products/{id}	Get product by ID


Cart APIs

Method	Endpoint	Description

POST	/api/cart/add	Add product to cart
GET	/api/cart	View cart items


Order APIs

Method	Endpoint	Description

POST	/api/order	Place order
GET	/api/order/{id}	Get order details



---

⚙ How to Run

Backend

1. Clone the repository
2. Update application.properties with MySQL credentials
3. Run the Spring Boot application

Frontend

1. Navigate to the React app folder
2. Run: npm install
3. Start development server: npm start


---

📷 Screenshots (Add your images)

Home Page

Product Listing Page

Cart Page

Checkout Page

Order Summary



---

🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.


---

⭐ Show Your Support

If this project helped you, please consider giving it a star on GitHub!

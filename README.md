Building a Containerized Book Management API
Objective: Creating a RESTful API for managing a book database using Flask, SQLAlchemy, and MariaDB, then containerizing the application.

Steps:
1. Use Flask to create the API
2. Use SQLAlchemy as the ORM to interact with MariaDB
3. Implement CRUD operations for books
4. Containerize the application using Docker
5. Use docker-compose to manage the app and database containers

API Endpoints:
1. GET /api/name: Get the API name
2. GET /books: Retrieve all books
3. POST /books: Create a new book
4. GET /books/<int:book_id>: Retrieve a specific book by ID
5. PUT /books/<int:book_id>: Update a specific book by ID
6. DELETE /books/<int:book_id>: Delete a specific book by ID
7. POST /api/check-duplicate: Check for duplicate books

Running the Application
Build and run the Docker containers: docker-compose up --build
Access the API at http://localhost:8080

Requirements
Flask
Flask-SQLAlchemy
Flask-Migrate
Flask-CORS
pymysql

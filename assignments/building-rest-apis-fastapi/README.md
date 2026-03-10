# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to design and implement RESTful APIs using the FastAPI framework in Python. By completing this assignment, students will understand the basics of API endpoints, request/response handling, and data validation.

## 📝 Tasks

### 🛠️ Project Setup

#### Description
Set up a new FastAPI project and create a basic application structure.

#### Requirements
Completed program should:
- Install FastAPI and Uvicorn
- Create a main Python file (e.g., main.py) with a FastAPI app instance
- Add a root endpoint (GET /) that returns a welcome message

### 🛠️ Create CRUD Endpoints

#### Description
Implement RESTful endpoints for managing a simple resource, such as books or users.

#### Requirements
Completed program should:
- Define a Pydantic model for the resource (e.g., Book with title, author, and id)
- Implement endpoints to:
  - Create a new resource (POST)
  - Retrieve all resources (GET)
  - Retrieve a resource by id (GET)
  - Update a resource by id (PUT)
  - Delete a resource by id (DELETE)
- Use in-memory storage (e.g., a Python list) for simplicity

#### Example Input/Output

- **POST /books**
  - Input:
    ```json
    { "title": "1984", "author": "George Orwell" }
    ```
  - Output:
    ```json
    { "id": 1, "title": "1984", "author": "George Orwell" }
    ```

- **GET /books/1**
  - Output:
    ```json
    { "id": 1, "title": "1984", "author": "George Orwell" }
    ```

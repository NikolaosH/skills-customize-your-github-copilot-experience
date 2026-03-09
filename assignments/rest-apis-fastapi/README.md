# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a RESTful API using the FastAPI framework in Python. Learn to create endpoints for handling HTTP requests and responses, manage data, and implement basic CRUD operations.

## 📝 Tasks

### 🛠️ Set Up FastAPI Project

#### Description
Install FastAPI and create a basic project structure with a simple endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a main.py file with FastAPI app
- Define a GET endpoint at "/" that returns a JSON response with a welcome message
- Run the server and verify the endpoint works

### 🛠️ Implement CRUD Endpoints

#### Description
Add endpoints for creating, reading, updating, and deleting items in a simple in-memory data store.

#### Requirements
Completed program should:

- Define a data model for items (e.g., using Pydantic)
- Create POST endpoint to add new items
- Create GET endpoint to retrieve all items or a specific item by ID
- Create PUT endpoint to update an item by ID
- Create DELETE endpoint to remove an item by ID
- Handle errors appropriately (e.g., item not found)
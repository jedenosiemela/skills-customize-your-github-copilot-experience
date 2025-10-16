# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build and test RESTful APIs using the FastAPI framework in Python. Students will create endpoints, handle requests, and return JSON responses.

## 📝 Tasks

### 🛠️ FastAPI Project Setup

#### Description
Set up a new FastAPI project and create a basic API endpoint.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a main Python file for the API
- Implement a root endpoint (`/`) that returns a welcome message in JSON format


### 🛠️ Create and Test REST Endpoints

#### Description
Add endpoints for basic CRUD operations (Create, Read, Update, Delete) for a simple resource (e.g., items).

#### Requirements
Completed program should:

- Define a data model for the resource (e.g., Item with id, name, description)
- Implement endpoints for:
  - Creating a new item (`POST /items`)
  - Reading all items (`GET /items`)
  - Reading a single item by id (`GET /items/{id}`)
  - Updating an item (`PUT /items/{id}`)
  - Deleting an item (`DELETE /items/{id}`)
- Return appropriate JSON responses for each operation
- Test endpoints using an API client (e.g., curl, Postman, or FastAPI's interactive docs)

# 📘 Assignment: Building REST APIs with FastAPI Framework

## 🎯 Objective

Create a REST API using FastAPI that handles basic CRUD operations for managing a collection of items (e.g., books, tasks, or products). Students will learn how to set up a FastAPI application, define endpoints, handle requests and responses, and implement data models.

## 📝 Tasks

### 🛠️	Set Up FastAPI Application

#### Description
Install FastAPI and create a basic FastAPI application with a root endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a FastAPI app instance
- Define a GET endpoint at "/" that returns a JSON response with a welcome message
- Run the server using Uvicorn


### 🛠️	Implement CRUD Operations

#### Description
Extend the FastAPI application to include full CRUD operations for a simple data model (e.g., Item with id, name, description).

#### Requirements
Completed program should:

- Define a Pydantic model for the Item
- Implement GET /items to retrieve all items
- Implement POST /items to create a new item
- Implement GET /items/{item_id} to retrieve a specific item
- Implement PUT /items/{item_id} to update an item
- Implement DELETE /items/{item_id} to delete an item
- Use in-memory storage (list or dict) for the items
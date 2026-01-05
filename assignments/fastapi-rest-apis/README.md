# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a RESTful API with FastAPI that exposes a small resource, validates requests with Pydantic models, and returns clear HTTP responses.

## 📝 Tasks

### 🛠️	Project Setup and Health Check

#### Description
Initialize a FastAPI project, run it locally, and expose a basic endpoint to confirm the server is healthy.

#### Requirements
Completed program should:

- Create a FastAPI app entrypoint (e.g., `main.py`) that runs with `uvicorn` and sets a descriptive title/version.
- Provide a `GET /health` endpoint that returns JSON `{ "status": "ok" }` and HTTP 200.
- Document run instructions in code comments or a short docstring so a peer can start the server.


### 🛠️	CRUD Resource: Books API

#### Description
Implement CRUD endpoints for a simple `Book` resource using FastAPI routing and Pydantic validation.

#### Requirements
Completed program should:

- Define a `Book` model with fields like `id`, `title`, `author`, and `year`, enforcing types and basic validation rules (e.g., non-empty title).
- Implement endpoints to list all books, fetch one by id, create, update, and delete; respond with appropriate HTTP status codes (201 on create, 404 when missing).
- Prevent duplicate IDs on create, and return informative error messages for invalid input or missing records.


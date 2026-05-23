# HTTP Basics

## What is HTTP?

HTTP = HyperText Transfer Protocol

It is the communication protocol between:

- Frontend
- Backend
- APIs
- Browsers
- AI services

---

## Why HTTP Matters

Modern applications communicate using HTTP.

Example:

Frontend → Backend  
Mobile App → API  
AI Service → Backend

---

## HTTP is Stateless

Each request is independent.

The server does not automatically remember previous requests.

---

## Common HTTP Methods

### GET

Retrieve data.

Example:

GET /users

---

### POST

Send data.

Example:

POST /chat

---

### PUT / PATCH

Update data.

---

### DELETE

Delete data.

---

## Request Structure

An HTTP request usually contains:

- Method
- URL
- Headers
- Body

Example:

Authorization: Bearer JWT_TOKEN

---

## Response Structure

A response usually contains:

- Status code
- Headers
- JSON data

Example:

{
  "message": "Success"
}

---

## Important Status Codes

### 200 OK

Success.

### 201 Created

Resource created successfully.

### 400 Bad Request

Client error.

### 401 Unauthorized

Authentication required.

### 403 Forbidden

Authenticated but not allowed.

### 404 Not Found

Resource not found.

### 500 Internal Server Error

Backend/server issue.

---

## Why HTTP Matters for AI Systems

AI applications rely heavily on APIs and HTTP communication.

Examples:

- Chat APIs
- Embedding APIs
- Authentication services
- AI gateways
# TaskFlow API

TaskFlow is a RESTful backend for managing personal tasks with dynamic
priority calculation and productivity analytics.

## Features

- User registration and authentication
- Task CRUD operations
- PostgreSQL persistence
- Dynamic task prioritization
- Productivity analytics

## Tech Stack

- Java 21
- Spring Boot
- Spring Web
- Spring Data JPA
- PostgreSQL
- Spring Security
- JWT
- Maven
- JUnit

## Planned API

POST   /api/auth/register
POST   /api/auth/login

GET    /api/tasks
POST   /api/tasks
GET    /api/tasks/{id}
PUT    /api/tasks/{id}
DELETE /api/tasks/{id}

GET    /api/analytics/summary

## Status

🚧 Currently under development.

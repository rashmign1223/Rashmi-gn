# Rashmi-gn
go- Backend development
//
# Go User API

RESTful API built using GoFiber, SQLC, PostgreSQL.

## Features
- CRUD users
- Dynamic age calculation
- Input validation
- Structured logging
- Clean architecture

## Setup

1. Create DB
2. Run migrations
3. Set env:
   export DATABASE_URL=postgres://user:pass@localhost:5432/dbname?sslmode=disable
4. Generate SQLC:
   sqlc generate
5. Run:
   go run cmd/server/main.go

## Endpoints
- POST /users
- GET /users/:id
- PUT /users/:id
- DELETE /users/:id
- GET /users

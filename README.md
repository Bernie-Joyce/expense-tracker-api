# expense-tracker-api

A backend REST API for tracking personal expenses.  
This project is being built over a fixed 10-day period before Christmas to gain hands-on experience with a new backend tech stack and to deliver a complete, end-to-end system.

## Purpose
The goal of this project is to design and implement a production-style backend service that allows users to record, view, update, and delete their expenses while ensuring proper data ownership, validation, and security.

This is not a tutorial project and no code is generated automatically. All logic, structure, and design decisions are implemented manually.

## Tech Stack
- Java
- Spring Boot
- Maven
- MySQL
- RESTful HTTP API
- Spring Data JPA
- Spring Security

## Core Features
- User registration and authentication
- Secure, user-scoped expense management
- Create, read, update, and delete expenses
- Expense categorisation
- Persistent storage using a relational database
- Input validation and structured error handling

## Non-Goals
The following are intentionally out of scope:
- Frontend or UI
- Budgeting or analytics
- Multiple currencies
- External integrations
- AI or automated code generation

## High-Level Design
- The API follows a layered architecture:
  - Controllers handle HTTP concerns only
  - Services contain business logic
  - Repositories manage persistence
- All expenses are owned by exactly one user
- Users cannot access or modify data they do not own

## Status
This project is actively under development.

# User Service

## Overview
Handles all user-related operations including authentication, authorization, and profile management.

## Tech Stack
- Java 17
- Spring Boot 3.x
- Spring Security
- PostgreSQL
- Redis

## API Endpoints
- `POST /api/v1/auth/login` - User login
- `POST /api/v1/users` - Create user
- `GET /api/v1/users/{id}` - Get user details
- `PUT /api/v1/users/{id}` - Update user

## Database
PostgreSQL database with user profiles and authentication data.

## Dependencies
- User Database (PostgreSQL)
- Redis Cache

## Team
Owned by **Team Bravo**
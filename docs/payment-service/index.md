# Payment Service

## Overview
Processes all financial transactions and integrates with external payment gateways.

## Tech Stack
- Python 3.11
- Django
- Django REST Framework
- PostgreSQL
- Stripe API

## Features
- Payment processing
- Subscription management
- Refund handling
- Invoice generation

## API Endpoints
- `POST /api/v1/payments` - Process payment
- `GET /api/v1/payments/{id}` - Get payment details
- `POST /api/v1/payments/{id}/refund` - Process refund

## Dependencies
- User Service
- Payment Database
- Stripe Payment Gateway

## Team
Owned by **Team Charlie**
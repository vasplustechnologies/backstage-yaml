# Admin Dashboard

## Overview
The Admin Dashboard is an internal web application used by TechCorp employees and administrators to manage platform operations, monitor services, and access administrative functions.

## Tech Stack
- Vue.js 3
- TypeScript
- Vite
- Vue Router
- Pinia (State Management)
- Element Plus UI Library

## Key Features
- **User Management**: View and manage user accounts
- **Service Monitoring**: Real-time service health dashboards
- **Payment Oversight**: Review and manage transactions
- **Inventory Control**: Monitor and update inventory levels
- **Analytics**: Business intelligence and reporting
- **Audit Logs**: View system activity and changes

## Architecture
The Admin Dashboard is a single-page application that communicates exclusively through the Mobile API Gateway. It has elevated permissions compared to the customer-facing portal.

## API Endpoints Used
- User Service (admin endpoints)
- Payment Service (admin endpoints)
- Inventory Service (admin endpoints)
- Analytics Service (custom reporting)

## Dependencies
- Mobile API Gateway
- User Service
- Payment Service
- Inventory Service

## Development Setup

```bash
# Clone repository
git clone https://github.com/techcorp/admin-dashboard
cd admin-dashboard

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
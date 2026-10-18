# Food Ordering Platform

A full-stack food ordering and restaurant management system designed for a single restaurant. The platform allows customers to place orders through a self-service kiosk and enables restaurant staff to manage incoming orders and food preparation.

## Project Objectives

The goal of this project is to design, develop, test, and deploy a production-style full-stack application while building practical experience with frontend development, backend engineering, databases, testing, and deployment.

## Project Scope

The platform will initially include three interfaces connected through a shared backend.

### 1. Customer Ordering Interface
- Browse the restaurant's menu.
- View item details and prices.
- Add items to a shopping cart.
- Enter a phone number during checkout.
- Place an order and receive a unique order ID.
- View order status.

### 2. Restaurant Dashboard
- View incoming customer orders.
- Verify order and payment status.
- Accept and prepare orders.
- Update order status as preparation progresses.
- Mark orders as ready for pickup.

### 3. Admin Interface
- Manage menu items, descriptions, and prices.
- Maintain the menu displayed to customers.
- Support basic restaurant administration.

### 4. Backend API
- Connect the customer, restaurant, and admin interfaces.
- Process orders and maintain their status.
- Store and retrieve menu and order data.
- Provide a foundation for authentication, authorization, and payment integration.

## Main Users

- **Customer:** Browses the menu and places an order.
- **Restaurant Staff:** Receives orders and manages food preparation.
- **Administrator:** Maintains menu information and manages the application.

## Order Workflow

1. The customer browses the menu and adds items to the cart.
2. The customer enters a phone number and submits the order.
3. The backend creates an order with a unique order ID.
4. The restaurant dashboard receives the order.
5. Staff verify payment status and accept the order.
6. Staff prepare the food and update the order status.
7. The customer collects the order using the order ID.

## Planned Technology Stack

- **Frontend:** React, TypeScript, Vite
- **Backend:** Java, Spring Boot, REST APIs
- **Database:** PostgreSQL
- **Version Control:** Git and GitHub
- **Testing and Deployment:** To be introduced as the project develops

## High-Level Architecture

Customer Ordering Interface ──┐

Restaurant Dashboard ──────────┼── Backend API ── Database

Admin Interface ───────────────┘

All three interfaces communicate with the backend API, which manages application data and business logic.

## Development Approach

The project will be developed incrementally, starting with repository setup and basic application structure, followed by menu management, order placement, restaurant order processing, testing, and deployment.

## Project Status

**In Progress** — Initial project planning and repository setup.

## Future Enhancements

- Staff accounts and role-based access control.
- Real-time order updates.
- Payment gateway integration.
- Order history and reporting.
- Automated testing, containerization, and cloud deployment.


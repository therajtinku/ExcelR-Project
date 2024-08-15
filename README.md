# ExcelR Store

## Overview

**ExcelR Store** is a comprehensive e-commerce platform designed for seamless online buying and selling of products and services. The platform provides both customers and administrators with robust features that ensure a smooth and secure online shopping experience.

## Key Features

### Shopper Interface
- **Product Browsing and Searching:** Easily navigate through product categories with detailed product information, including price, description, images, and available stock.
- **Shopping Cart Functionality:** Add products to a virtual cart, modify quantities, or remove items before proceeding to checkout.
- **Checkout Process:** Secure checkout with shipping details, payment options, and order summary, integrated with Razorpay for secure transactions.

### Admin Interface
- **Dashboard:** Comprehensive overview of store operations, including sales statistics, recent orders, and user activity.
- **Orders Management:** View, update, and manage all customer orders, tracking their status (e.g., pending, shipped, delivered).
- **Products Management:** Add, update, or remove products from the catalog, managing details, prices, and inventory levels.
- **Categories Management:** Create and organize product categories for easier navigation.
- **User Management:** View and manage registered users, update roles, manage access rights, and handle customer service needs.

### User Authentication and Authorization with Spring Security
- **Spring Security:** Handles authentication and authorization processes, protecting sensitive routes and ensuring secure access.
- **Role-Based Authentication:** Role-based access control (RBAC) grants different levels of access based on user roles (e.g., shopper, admin).
- **JSON Web Token (JWT) Authentication:** Securely manage user sessions with JWT, authenticating and authorizing users for protected resources.

### Core Entities
- **User Entity:** Stores essential user information, including name, email, password, and roles.
- **Product Entity:** Manages the product catalog with details like name, description, price, image, and category.
- **Order Entity:** Represents customer orders with product details, quantities, prices, shipping information, and order status.
- **Cart Entity:** Manages the shopping cart for each user, linking to the user and used during checkout.

## Project Output

The project includes the following pages:
- Home Page <a href="https://i.imgur.com/WE9Bydv.jpg" target="_blank">![Home Page](https://i.imgur.com/WE9Bydv.jpg)</a>

- Register Page <a href="https://i.imgur.com/MJEEg4S.png" target="_blank">![Register Page](https://i.imgur.com/MJEEg4S.png)</a>

- Login Page <a href="https://i.imgur.com/uoghuWe.jpg" target="_blank">![Home Page](https://i.imgur.com/uoghuWe.jpg)</a>

- Admin Page <a href="https://i.imgur.com/J8JYSfa.jpg" target="_blank">![Home Page](https://i.imgur.com/J8JYSfa.jpg)</a>

- Add Products Page <a href="https://i.imgur.com/p93IYL3.jpg" target="_blank">![Home Page](https://i.imgur.com/p93IYL3.jpg)</a>

- Product Detail Page <a href="https://i.imgur.com/zMe1cia.jpg" target="_blank">![Home Page](https://i.imgur.com/zMe1cia.jpg)</a>

- Cart Page <a href="https://i.imgur.com/D3WRgzw.jpg" target="_blank">![Home Page](https://i.imgur.com/D3WRgzw.jpg)</a>

- Billing Page <a href="https://i.imgur.com/6XnO75l.jpg" target="_blank">![Home Page](https://i.imgur.com/6XnO75l.jpg)</a>

- Payment Page <a href="https://i.imgur.com/mXebOiu.jpg" target="_blank">![Home Page](https://i.imgur.com/mXebOiu.jpg)</a>

- Order Placed Page <a href="https://i.imgur.com/CSM5JgC.jpg" target="_blank">![Home Page](https://i.imgur.com/CSM5JgC.jpg)</a>

- My Orders Page <a href="https://i.imgur.com/CSM5JgC.jpg" target="_blank">![Home Page](https://i.imgur.com/CSM5JgC.jpg)</a>

## Technology Stack

- **Backend:** Java with Spring Boot
- **Frontend:** React.js
- **Database:** MySQL
- **Security:** Spring Security with JWT
- **Payment Gateway:** Razorpay


# 🛒 Laravel-Based CRM and E-Commerce Backend System

Welcome to the repository for the **Laravel-Based CRM and E-Commerce Backend System**. This project is designed to help businesses manage customers, products, and transactions efficiently using a secure, scalable backend system.

## 📖 Project Overview

This project aims to streamline e-commerce operations by providing a comprehensive CRM system. It supports customer management, product management, and transaction processes with robust security mechanisms. The system is built on the **Laravel Framework** and includes API-driven communication for seamless integration with mobile and web platforms.

## 🛠️ Key Features

### Customer Functionalities
- **User Registration**: Customers can create accounts via the mobile app.
- **Profile Management**: Customers can update their profiles.
- **Product Browsing**: Customers can view available products.

### Admin Functionalities
- **Product Management**: Admins can create, read, update, and delete (CRUD) products.
- **Customer Management**: Admins manage customer details and records.
- **Analytics Dashboard**: Sales and customer insights for effective business management.

## 🚀 Technology Stack

- **Frontend**: Built using Bootstrap, AlpineJS, and Livewire.
- **Backend**: Laravel framework with Sanctum for API authentication.
- **Database**: MySQL.
- **APIs**: CRUD operations for managing products and customers via a secure API.

## 📚 System Design

The system follows a relational database model, including entities such as Customers, Products, and Orders. Here are some design highlights:
- **ER Diagram**: Defines relationships between the core entities.
- **Use Case Diagram**: Shows interactions between the customers, system, and admins.
- **Authentication**: Secured using Laravel Sanctum for API token-based authentication.
  

## 📲 **Screenshots**

![registratopn page](https://github.com/user-attachments/assets/98e08d0e-484c-4bfa-8855-42bca57792ff)
![login page](https://github.com/user-attachments/assets/f9312a2e-0a59-4275-a244-bf70320e140d)
![admin dashboard](https://github.com/user-attachments/assets/5f42237f-adf8-4671-8680-49db4bd2da70)
![product dashboard](https://github.com/user-attachments/assets/f964d70b-828f-45e0-a50d-f53379225262)
![customer dashboard](https://github.com/user-attachments/assets/47beeabd-d0e6-4343-ae8b-e230e2e878e3)
![delete customer success](https://github.com/user-attachments/assets/7de3aefb-ea94-4c4a-98dd-2555646ed08d)
![view customers](https://github.com/user-attachments/assets/c5bd5a6a-cbd0-4e28-b928-2f1b2c6db4de)
![add customer](https://github.com/user-attachments/assets/ed75a39c-ada3-4542-a8cb-1f9e058b2204)



## 📡 API Endpoints

Here are some example API endpoints used in the system:

- **Product Management**:
  - `GET /api/products` - List all products.
  - `POST /api/products` - Create a new product.
  - `PUT /api/products/{id}` - Update an existing product.
  - `DELETE /api/products/{id}` - Delete a product.

- **Customer Management**:
  - `GET /api/customers` - List all customers.
  - `POST /api/customers` - Add a new customer.
  - `PUT /api/customers/{id}` - Update customer details.
  - `DELETE /api/customers/{id}` - Delete a customer.

## 🧪 Testing & Quality Assurance

The project has been tested using various methods, including:
- **Functional Testing**: 10+ test cases to verify API functionality.
- **Usability Testing**: Ensured ease of navigation and usability.
- **Performance Testing**: Stress tests were performed to ensure high performance under load.

## 🚧 Future Development

### SaaS Expansion Plan
The system is designed with future scalability in mind and could evolve into a SaaS platform. Key features of the SaaS version would include:
- **Multi-Tenancy**: Support for multiple businesses under one system.
- **Subscription Plans**: Different tiers for businesses based on features.
- **Custom Branding**: Tenant-specific customization options for UI and branding.
- **Advanced Analytics**: In-depth customer and product reports.

## 📝 License

This project is licensed under the MIT License.

## 👏 Show Your Support

If you find this project useful, please consider giving it a ⭐️!

---

[GitHub Repository](https://github.com/EldersMahithSheshan/Ecommerce-app)

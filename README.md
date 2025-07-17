# PharmacyManagement
A full-stack web app built with MERN stack (MongoDB, Express, React, Node.js) for efficient medicine stock tracking, automated billing, and sales analytics. Features include low-stock alerts, invoice generation, JWT authentication, and role-based access control. Uses MongoDB Atlas for cloud storage and offers responsive UI for all devices.

## Table of Contents
- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Folder Structure](#folder-structure)
- [License](#license)

## Overview
This project provides a management system with separate dashboards for admins and users, supporting authentication, CRUD operations for customers, products, suppliers, purchases, sales, and stock management.

## Tech Stack
- **Frontend:** React, Ant Design, Recharts, React Router
- **Backend:** Node.js, Express, MongoDB, Mongoose
- **Other:** Axios, Bootstrap, dotenv, CORS

## Features
- User and Admin authentication: Secure login for users and admins.
- Role-based Dashboard: Separate dashboards and navigation for Admin and User roles.
- Financial Overview: Dashboard displays total purchases, total sales, current stock value, and net profit/loss.
- Inventory Controls: Quick search and filtering by product name, generic name, category, and supplier.
- Dynamic Thresholds: Set low stock and near-expiry thresholds directly from the dashboard.
- Inventory Status Widgets: Real-time display of out-of-stock, low stock, near expiry, and expired medicines.
- Product Management: Add, edit, and delete products with details like generic name, category, purpose, and GST.
- Customer Management: Add, edit, and delete customers; search by name, contact, or email.
- Supplier Management: Add, edit, and delete suppliers with organization and contact details.
- Stock Management: View, search, and manage stock with batch, expiry, supplier, and quantity details.
- Invoice Management: Create, view, edit, and print invoices; supports discounts, GST, and multiple payment types.
- Purchase Management: Add and manage purchases with supplier, batch, expiry, and product details.
- Sales & Purchase Analytics: Visual dashboards for sales and purchase trends, monthly/annual comparisons, and top products.
- Credential Management: Admins can add new users and update credentials for both users and admins.
- Logout Functionality: Secure logout for all users.
- **Low Stock Alerts:** Automatically notifies users/admins when the stock of any product falls below a predefined threshold, helping to prevent shortages.
- **Expired Medicines:** Tracks expiry dates of medicines and highlights or alerts when medicines are expired or nearing expiration, ensuring safety and compliance.
- **Out of Stock:** Clearly marks products that are out of stock, preventing their sale and helping with timely reordering.
- **Seasonal Medicines:** Allows identification and management of medicines that are in higher demand during certain seasons, supporting better inventory planning.


## Screenshots

All screenshots for this project can be viewed in the following Google Drive folder:

[View Screenshots on Google Drive](https://drive.google.com/drive/folders/1LJecWK08uuWMfpaYlTbdID9fH0CE8lu7?usp=sharing)

## Getting Started

### Backend Setup
1. Navigate to the backend folder:
   ```bash
   cd lastandfinal/backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file with your MongoDB URI and other environment variables as needed.
4. Start the backend server:
   ```bash
   npm start
   ```
   The backend runs on [http://localhost:5000](http://localhost:5000) by default.

### Frontend Setup
1. Open a new terminal and navigate to the frontend folder:
   ```bash
   cd lastandfinal/last
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend app:
   ```bash
   npm start
   ```
   The frontend runs on [http://localhost:3000](http://localhost:3000) by default.

## Folder Structure
```
lastandfinal/
  backend/         # Express backend (API, models, controllers)
  last/            # React frontend (src, public, components, pages)
  screenshots/     # (Optional) Place your screenshots here
```

## License
This project is licensed under the MIT License.


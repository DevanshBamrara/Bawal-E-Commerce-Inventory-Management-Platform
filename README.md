# Bawal E-Commerce & Inventory Management Platform

A comprehensive, full-stack e-commerce and inventory management solution built for a Gen-Z clothing brand. This repository contains the complete project, functionally separated into three core modules: the customer storefront, the admin dashboard, and the backend API.

---

## 🌐 Live Demos

- **🛍️ Customer Storefront:** [https://bawal-store.vercel.app/](https://bawal-store.vercel.app/)
- **🛡️ Admin Dashboard:** [https://bawal-admin-git-main-bamraradevansh-7503s-projects.vercel.app/](https://bawal-admin-git-main-bamraradevansh-7503s-projects.vercel.app/)
- **⚙️ Backend API (Swagger UI):** [https://bawal-api.onrender.com/swagger-ui/index.html#](https://bawal-api.onrender.com/swagger-ui/index.html#)

---

## 🏗 Project Structure

This monorepo consists of three main projects:

### 1. 🛍️ `bawal-store` (Customer Front-End)
The public-facing e-commerce storefront where customers can browse the catalog and place orders.
- **Tech Stack:** React 19, Vite, React Router DOM, Lucide React (Icons)
- **Features:** Catalog browsing, cart management, responsive UI.

### 2. 🛡️ `bawal-admin` (Admin Front-End)
The internal admin dashboard used by staff and management to oversea the storefront and stock.
- **Tech Stack:** React 19, Vite, React Router DOM, Lucide React (Icons)
- **Features:** Inventory management, order tracking, responsive dashboard layouts.

### 3. ⚙️ `bawal-backend` (Backend API)
The core REST API serving both the storefront and admin panels, handling business logic, data persistence, and inventory synchronization.
- **Tech Stack:** Java 17, Spring Boot 3.4.3, Spring Data JPA, Lombok
- **Database:** PostgreSQL (Production) / H2 (Development & Testing)
- **Documentation:** Swagger/OpenAPI (Springdoc)

---

## 🚀 Getting Started

### Prerequisites
- **Node.js**: v18+ (Required for `bawal-store` and `bawal-admin`)
- **Java**: JDK 17+ (Required for `bawal-backend`)
- **Maven**: 3.8+ (Used as build tool for the backend)

### 1. Running the Backend API (`bawal-backend`)
```bash
cd bawal-backend
# Run the Spring Boot application (Default port: 8080)
./mvnw spring-boot:run
```
*API Documentation (Swagger UI) is typically available at: `http://localhost:8080/swagger-ui.html`*

### 2. Running the Admin Dashboard (`bawal-admin`)
```bash
cd bawal-admin
# Install dependencies
npm install
# Start the Vite development server
npm run dev
```

### 3. Running the Customer Storefront (`bawal-store`)
```bash
cd bawal-store
# Install dependencies
npm install
# Start the Vite development server
npm run dev
```

---

## 🛠 Features & Capabilities
- **Responsive Design:** Both frontend apps (`admin` and `store`) are fully responsive across all devices (mobile, tablet, desktop).
- **Real-Time Inventory Integration:** Seamless data flow ensuring stock levels dictate precise availability on the storefront.
- **Unified Backend logic:** A central Spring Boot backend cleanly exposing separated capabilities (Orders, Inventory, Store Settings).

---

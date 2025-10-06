# Monolith_To_Microservices_In_Go

# 🏗️ Go E-commerce Application — Monolith to Microservices Migration

This project is an end-to-end implementation of an **E-commerce platform** in **Go (Golang)** that starts as a **Monolithic application** and is later **migrated to a Microservices architecture**.  
The goal of this project is to gain a deep understanding of how to design, build, and refactor Go applications for scalability and distributed environments.

---

## 🧠 Project Overview

The project simulates a C2C (Customer-to-Customer) E-commerce platform where users can register as buyers or sellers, manage products, make purchases, and receive notifications.

Initially, the project is built as a **Monolith**, and then refactored into **Microservices** with clear boundaries like:
- User Service
- Product Service
- Payment Service
- Notification Service

---

## 🧩 Image


🔗 [Migrate from Monolith to Microservices Architecture](https://itechindia.co/blog/migrate-from-monolith-to-microservices-architecture/)


---

## 🧱 1. Functional Requirements

### 👥 Users
- User Sign-up / Login functionality  
- User verification with OTP / SMS  
- User can become a seller or buyer  

### 🛍️ Catalog
- Product Listing  
- Manage Products (Create / Update / Delete Products)  
- Stock Management  

### 💳 Payment
- Buyer can purchase products using online payment (Card / Online Banking, etc.)  

### 🔔 Notifications
- Email  
- SMS  

---

## ⚙️ 2. Non-Functional Requirements

1. System should be **highly available** in the cloud with multiple regions (C2C portal).  
2. System should maintain **best practices** to scale horizontally at any level.  
3. System design should allow **modularization into microservices**.  
4. Ensure **loosely coupled services** and clear communication between them.  
5. Include **logging and monitoring** to inspect service health and availability.  
6. Maintain **clear documentation** for API usage, architecture, and business logic.  
7. Ensure **usability and maintainability** for future developers and scaling.  


## 📚 Learning Goals

- Understand how to design scalable architectures in Go.  
- Learn to migrate Monolithic applications to Microservices.  
- Implement real-world communication patterns (REST, gRPC, Message Queues).  
- Explore deployment strategies for distributed Go systems.


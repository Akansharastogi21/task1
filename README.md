# E-commerce Database Schema

## 📌 Overview
This project contains an E-commerce database schema designed as part of the SQL Developer Internship Task 1.  
The schema supports users, products, orders, payments, and order details.

## 🛠 Tools Used
- MySQL Workbench
- ER Diagram tool (MySQL Workbench / Draw.io)

## 📂 Schema Design
- Users can place multiple orders.
- Each order can have multiple products.
- Each product can belong to multiple orders.
- Each order has a payment record.

## 📊 ER Diagram
![ER Diagram](er-diagram.png)

## 📜 SQL Script
See [`ecommercedb`](ecommercedb) for database creation.

## 🎯 Key Concepts
- DDL (CREATE TABLE, FOREIGN KEY)
- Normalization (3NF applied)
- ER Diagrams

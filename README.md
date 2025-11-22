## Odoo_Hackathon

Problem Statement : StockMaster

Team Details : Mohammed Hussain Shaikh, Abhishek A Pillai, Prashant Mahadev Goundadkar, P. Anurag

Reviewer Name : Aman Patel (ampa)



# StockMaster – Inventory Management System

StockMaster is a modular and user-friendly Inventory Management System (IMS) designed to replace manual registers, Excel sheets, and scattered stock tracking with a centralized, real-time platform.
It provides complete control over products, warehouses, stock movements, and operational documents.

## 🚀 Features


### 🔐 Authentication

User signup & login

OTP-based password reset

Redirects to Dashboard after login

### 📊 Dashboard Overview

Real-time KPIs such as:

Total products in stock

Low-stock & out-of-stock alerts

Pending receipts & deliveries

Internal transfers

Document filters by status, category & warehouse

### 📦 Core Modules
1. Product Management

Add & update products

SKU / Code, category, UOM

Stock availability by location

Reordering rules

2. Receipts (Incoming Stock)

Process goods arriving from suppliers:

Create receipt

Add supplier & items

Enter received quantities

Validate → stock increases automatically

3. Delivery Orders (Outgoing Stock)

Process outgoing goods for customers:

Pick items

Pack items

Validate → stock decreases automatically

4. Internal Transfers

Move goods between:

Warehouses

Racks

Production floors

All movements are logged in the ledger.

5. Stock Adjustments

Fix mismatches between recorded and physical stock:

Select product/location

Enter counted quantity

System updates & logs differences

### 🏭 Target Users

Inventory Managers – handle product entries & stock movements

Warehouse Staff – picking, shelving, transfers, counting

### 🧠 Additional Features

Multi-warehouse support

Smart filters and SKU search

Low-stock alerts

Full movement ledger

### 📘 Simplified Example Flow

Receive Goods – Stock +100

Internal Transfer – Moves stock between racks

Deliver Goods – Stock –20

Adjust Damaged Stock – Stock –3

Everything is recorded in the Stock Ledger.

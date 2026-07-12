# 🛒 Online Shopping Store

A full-featured e-commerce web application built with **ASP.NET MVC 5**, allowing customers to browse products, add items to cart, and place orders — with a complete administrative panel for managing the store's catalogue.

---

## 🧰 Tech Stack

| Technology | Purpose |
|---|---|
| **ASP.NET MVC 5** | Core web framework |
| **Entity Framework (Database First)** | ORM / Data access layer |
| **SQL Server** | Relational database |
| **Bootstrap** | Responsive UI styling |
| **C#** | Server-side logic |

---

## ✨ Features

### 👤 Customer Side
- 🗂️ Product catalogue organized by categories
- 🔥 Display of most popular items
- 🔐 User login & registration
- 🛍️ Add to cart functionality
- ✅ Submit order / checkout

### 🛠️ Admin Panel
- ➕ Create new product
- ✏️ Update existing product
- 🔍 View detailed product information
- 🗑️ Delete product
- ➕ Create new category
- ✏️ Update category
- 🔍 View detailed category information
- 🗑️ Delete category

---

## 🏗️ Architecture

This project follows the **MVC (Model-View-Controller)** pattern with **Entity Framework Database-First** approach:

- **Model** — Entity Framework generated models mapped from SQL Server database
- **View** — Razor views styled with Bootstrap for a responsive UI
- **Controller** — Handles business logic for products, categories, cart, orders, and admin operations

---

## 🚀 Getting Started

### Prerequisites
- Visual Studio (2017 or later recommended)
- SQL Server (LocalDB or full instance)
- .NET Framework (compatible with MVC 5)
2. Open the solution in Visual Studio
3. Update the connection string in `Web.config` to point to your SQL Server instance
4. Run Entity Framework database migration / ensure the database schema matches the EDMX model
5. Build and run the project (`F5`)

---

## 📄 License

This project is open for educational and portfolio purposes.

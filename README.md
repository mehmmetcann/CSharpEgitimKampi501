# CSharpEducation501 – WinForms & Dapper Project

This repository contains an educational and practical project developed by following the **C# Education Camp – Dapper Module**. The project is built using **Windows Forms**, **Dapper**, **Repository Pattern**, and **DTO-based architecture**, focusing on clean code and real-world data access practices. All concepts taught in the training were directly applied in this project.

---

## 🎯 Project Purpose

The main goal of this project is to gain hands-on experience with using **Dapper** for fast and lightweight data access, performing **CRUD operations** with SQL Server, applying **Repository Pattern** to separate concerns, using **DTO (Data Transfer Object)** for safe and clean data transfer, and structuring WinForms applications with a maintainable architecture. This project is designed to serve as a strong foundation for **internship and junior software developer positions**.

---

## 📚 Training Topics Covered

This project was developed by following these topics from the **C# Education Camp**: Introduction to Dapper, Dapper Installation and Configuration, Executing SQL Queries with Dapper, CRUD Operations (Create, Read, Update, Delete), Repository Pattern Implementation, Interface-based Data Access, DTO usage (Create, Update, Result DTOs), and WinForms Integration with the Data Access Layer.

---

## 🧱 Architecture Overview

The project follows a layered and responsibility-based structure, even though it is a WinForms application. DTOs are used to transfer data safely, the Repository Layer handles all database operations using Dapper, and the Presentation Layer (WinForms) manages user interaction and displays data on the UI. There is no direct database access from the UI layer, ensuring clean separation of concerns.

---

## 🔄 Layer Communication Flow

Presentation Layer (WinForms) → Repository Layer → Dapper → SQL Server Database

---

## 🖥️ Application Features

Product listing, adding new products, updating existing products, deleting products, and fast, lightweight data access using Dapper.

---

## 🛠 Technologies and Concepts Used

C#, .NET Framework, Windows Forms, Dapper, SQL Server, Repository Pattern, DTO (Data Transfer Object), and Object-Oriented Programming (OOP).

---

## ▶️ Running the Project

1. Clone the repository using: `git clone https://github.com/mehmmetcann/CSharpEgitimKampi501.git`
2. Open the `.slnx` file with **Visual Studio**
3. Configure the database connection in `App.config`
4. Run the project

---

## 📌 Key Takeaways

Through this project, I gained practical experience with using Dapper as a micro-ORM, writing efficient SQL-based data access code, applying Repository Pattern in WinForms applications, structuring projects with clean and maintainable code, and understanding the difference between Entity Framework and Dapper usage scenarios. This repository represents my **hands-on learning process** and serves as a reference project for real-world Dapper usage.

---

## 📝 License

This project is licensed under the **MIT License**.

---

## 👤 Developer

**Mehmet Can**  
Computer Engineering Student  

This project was developed for educational and self-improvement purposes.

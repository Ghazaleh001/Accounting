# 💰 Accounting System

A layered accounting management application built with **C# and .NET**.
The project is structured into separate layers to keep the application maintainable, organized, and easier to extend.

This project includes:

* 🧩 Layered Architecture
* 💻 C# / .NET
* 🗄️ Database-First
* 🔄 Repository Pattern
* 🧠 Business Logic Layer
* 📦 ViewModel Layer
* 🛠️ Utility Layer
* 🖥️ Desktop Application

---

## 📌 Features

* **Layered Architecture:** Separates the application into different responsibilities.
* **Data Access Layer:** Handles communication with the database.
* **Business Layer:** Contains the application's business logic.
* **ViewModel:** Provides models used for transferring data between different parts of the application.
* **Repository Pattern:** Provides an abstraction for data-access operations.
* **Utility Classes:** Contains reusable helper functionality.
* **Entity Framework:** Used for database-related operations.
* **Object-Oriented Design:** Built using C# and object-oriented programming principles.

---

## 🏗️ Project Structure

```text
Accounting
│
├── Accounting.App          # Application / User Interface
├── Accounting.Business     # Business logic and services
├── Accounting.DataLayer    # Database and data access
├── Accounting.Utility      # Shared utilities and helpers
├── Accounting.ViewModel    # ViewModels and data transfer
├── ConsoleApp1             # Console application
└── Accounting.sln          # Solution file
```

### Accounting.App

The main application layer responsible for the user interface and interaction with the system.

### Accounting.Business

Contains the business logic of the application and coordinates operations between the application and data layers.

### Accounting.DataLayer

Responsible for database communication and data persistence.

### Accounting.ViewModel

Contains ViewModels used to transfer and prepare data between the application layers.

### Accounting.Utility

Contains reusable helper classes and common functionality used throughout the application.

---

## 🚀 Getting Started

### Prerequisites

Before running the project, make sure you have:

* Visual Studio
* .NET SDK compatible with the project
* SQL Server
* Entity Framework dependencies

### Setup

1. Clone the repository:

```bash
git clone https://github.com/Ghazaleh001/Accounting.git
```

2. Open the solution:

```text
Accounting.sln
```

3. Restore the NuGet packages.

4. Configure the database connection according to your local environment.

5. Build the solution.

6. Run the application.

---

## 🗄️ Database

The project uses a relational database to store and manage application data.

Database-related operations are separated into the `Accounting.DataLayer` project, keeping database logic independent from the application's business and presentation layers.

---

## 🔧 Technologies

* **C#**
* **.NET**
* **Entity Framework**
* **SQL Server**
* **Object-Oriented Programming (OOP)**
* **Layered Architecture**
* **Repository Pattern**
* **Git & GitHub**

---

## 🎯 Project Goals

The main goal of this project is to implement an accounting application while practicing real-world software development concepts such as:

* Designing a multi-layered application
* Working with databases
* Implementing business logic separately from the UI
* Applying OOP principles
* Using Entity Framework
* Working with repositories
* Organizing a large .NET solution into independent projects


GitHub:
https://github.com/Ghazaleh001

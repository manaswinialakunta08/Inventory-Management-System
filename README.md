# 📦 Inventory Management System

A **command-line Inventory Management System built with Python** to manage products, stock levels, pricing, and inventory records using persistent JSON file storage.

This project was developed to apply core Python programming concepts to a practical real-world problem.

---

## 🚀 Features

* ➕ Add new products
* 📋 View all products
* 🔍 Search products
* ✏️ Update product details
* 🗑️ Delete products
* ⚠️ Identify low-stock products
* 💰 Track product prices and quantities
* 💾 Persistent data storage using JSON
* 🛡️ Basic input validation and exception handling
* 🖥️ Simple command-line interface

---

## 🛠️ Tech Stack

**Language**

* Python 🐍

**Concepts & Modules**

* Functions
* Dictionaries
* Lists
* Loops
* Conditional Statements
* CRUD Operations
* File Handling
* JSON
* Exception Handling
* `pathlib`

---

## 📂 Project Structure

```text
Inventory-Management-System/
│
├── main.py
├── inventory.json
└── README.md
```

### `main.py`

Contains the main application logic, menu system, and inventory operations.

### `inventory.json`

Stores inventory data persistently in JSON format.

### `README.md`

Project documentation and usage instructions.

---

## ⚙️ How It Works

The application follows a simple workflow:

```text
            Start
              │
              ▼
       Display Main Menu
              │
      ┌───────┼────────┐
      ▼       ▼        ▼
    Add     Search    View
      │       │        │
      └───────┼────────┘
              ▼
          Update
              │
              ▼
           Delete
              │
              ▼
        Save to JSON
              │
              ▼
             Exit
```

All inventory changes are saved to `inventory.json`, allowing the data to remain available when the application is run again.

---

## ▶️ Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Navigate to the project directory

```bash
cd Inventory-Management-System
```

### 3. Run the application

```bash
python main.py
```

---

## 🖥️ Application Menu

```text
====================================
       INVENTORY MANAGEMENT SYSTEM
====================================

1. Add Product
2. View Products
3. Search Product
4. Update Product
5. Delete Product
6. Low Stock Products
7. Exit

Enter your choice:
```

---

## 📦 Example Inventory Data

The inventory is stored in JSON format:

```json
{
    "101": {
        "name": "Keyboard",
        "price": 1200,
        "quantity": 10
    },
    "102": {
        "name": "Mouse",
        "price": 600,
        "quantity": 5
    }
}
```

---

 Outcomes

Through this project

* Writing modular Python programs
* Creating reusable functions
* Working with dictionaries and structured data
* Performing CRUD operations
* Reading and writing files
* Working with JSON data
* Handling errors and invalid input
* Building a menu-driven CLI application
* Maintaining persistent application data


## 🔮 Future Improvements

The project can be extended with:

* [ ] SQLite/MySQL database integration
* [ ] Product categories
* [ ] Supplier management
* [ ] Sales and purchase tracking
* [ ] Automatic stock updates
* [ ] Inventory value reports
* [ ] CSV import/export
* [ ] User authentication
* [ ] GUI interface
* [ ] Web-based version
* [ ] REST API

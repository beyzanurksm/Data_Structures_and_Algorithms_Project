# 📦 Cargo Management System

A console-based **Cargo Management System** developed with Python.

This project simulates basic cargo operations such as customer registration, shipment creation, delivery status tracking, shipment history management, and delivery route visualization.

---

## 🎯 Project Purpose

The main purpose of this project is to model a cargo management process by using fundamental data structures and algorithms.

The system allows users to manage customers, add shipments, check delivery status, view shipment history, list cargo records, and display delivery routes through a simple menu-based interface.

---

## 🧩 Main Functionalities

The application provides the following operations:

* Add a new customer
* Add a cargo shipment for an existing customer
* Query cargo delivery status by shipment ID
* View a customer’s shipment history
* List delivered and undelivered cargo records
* Sort undelivered shipments by delivery time
* Display delivery routes using a tree-based structure
* Run predefined test scenarios

---

## 🗂️ Data Structure Usage

Different data structures are used to represent different parts of the cargo system:

| Structure      | Usage                                            |
| -------------- | ------------------------------------------------ |
| Dictionary     | Stores customers by customer ID                  |
| Stack          | Keeps each customer’s shipment history           |
| Priority Queue | Prioritizes shipments according to delivery time |
| Tree           | Represents city-based delivery routes            |
| Binary Search  | Searches delivered shipment IDs efficiently      |
| Merge Sort     | Sorts undelivered shipments by delivery time     |

---

## 📌 Menu Options

When the program runs, users can interact with the system through the following menu:

```text
1. Add a new customer
2. Add a cargo shipment
3. Query cargo status
4. View shipment history
5. List all cargo records
6. Display delivery routes
7. Show test scenarios
0. Exit
```

These menu options allow the user to test and manage the main features of the cargo system from the terminal.

---

## 👥 Contributors

This project was developed collaboratively.

* [Beyzanur Kasım](https://github.com/byznrksm)
* [BeyzaNurCom](https://github.com/BeyzaNurCom)

---

## 📄 Note

This project was created to demonstrate the use of data structures and algorithms in a cargo management scenario.

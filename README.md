# **Object-Oriented Programming (OOP) Projects**

This repository contains multiple projects and examples developed as part of my **Object-Oriented Programming (OOP)** course. These projects demonstrate the principles of OOP, such as encapsulation, polymorphism, and modular design, using practical scenarios like reservation systems, bank account management, and geometric calculations.

---

## **Overview**

Each project focuses on a specific real-world application of OOP concepts. These examples aim to provide a comprehensive understanding of how to design, implement, and use object-oriented programs effectively.

---

## **Projects**

### **1. Reservation System**
A system that allows customers to book services such as hotel rooms. It demonstrates:
- Customer management and reservation linking.
- Service availability checks and booking functionality.
- Modular design using separate classes for `Customer`, `Service`, and `Reservation`.

**Key Files**:
- `Customer.cpp`, `Customer.h`
- `Reservation.cpp`, `Reservation.h`
- `Service.cpp`, `Service.h`
- `main.cpp`

**Sample Features**:
- Add and view reservations for a customer.
- Book a service and manage availability.

---

### **2. Bank Account Management**
A simple program to simulate bank account operations such as deposits and withdrawals. It highlights:
- Encapsulation of account details.
- Methods for balance updates and checks.

**Key File**:
- `BankAccount.cpp`

**Features**:
- Deposit money into the account.
- Withdraw money with balance validation.
- Handle insufficient funds gracefully.

---

### **3. Rectangle Perimeter and Area Calculation**
A program for calculating the area and perimeter of a rectangle. It showcases:
- Class design for geometric shapes.
- Dynamic updates to object properties.

**Key File**:
- `Rectangle.cpp`

**Features**:
- Compute area and perimeter based on dimensions.
- Modify rectangle dimensions dynamically.
- Recalculate area and perimeter after updates.

---

## **Project Structure**

```plaintext
oop-projects/
│
├── Reservation System/
│   ├── Customer.cpp
│   ├── Customer.h
│   ├── Reservation.cpp
│   ├── Reservation.h
│   ├── Service.cpp
│   ├── Service.h
│   └── main.cpp
│
├── Bank Account/
│   └── BankAccount.cpp
│
└── Geometry/
    └── Rectangular.cpp

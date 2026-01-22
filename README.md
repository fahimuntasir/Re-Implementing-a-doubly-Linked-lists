## 🔗 Re-Implementing a Doubly Linked List (OOP Course Project)

A complete **object-oriented implementation of a Doubly Linked List** in **Java**, developed as part of the **Object-Oriented Programming (OOP)** course at **Hubei University of Technology**.

This project focuses on **data structure design**, **encapsulation**, **exception handling**, and **pointer manipulation** using Java classes and inheritance.

---

## 📌 Project Overview

The goal of this project is to **re-implement a doubly linked list from scratch** by extending abstract base classes provided in the course exercise.

The implementation strictly follows:

* Object-oriented principles
* Proper node validation
* Safe insertion, deletion, and traversal operations

A **sentinel (head) node** is used to simplify boundary conditions and improve robustness.

---

## 🎯 Objectives

* Implement a fully functional **Doubly Linked List**
* Apply **inheritance and abstraction**
* Handle invalid node operations using **custom exceptions**
* Strengthen understanding of **linked list internals**
* Practice **clean and safe pointer manipulation**

---

## 🧠 Key Concepts Used

* Doubly Linked List data structure
* Object-Oriented Programming (OOP)
* Abstract classes & inheritance
* Exception handling (`InvalidNodeException`)
* Sentinel (dummy head) node
* Encapsulation & data integrity

---

## 🧾 Class Structure

### Core Classes

* `List` (Abstract)
* `ListNode` (Abstract)
* `DList` (Concrete implementation)
* `DListNode` (Concrete node)
* `InvalidNodeException`

---

## ⚙️ Implementation Highlights

### ✔ DListNode Methods Implemented

* `next()`
* `prev()`
* `insertBefore(Object item)`
* `insertAfter(Object item)`
* `remove()`

### ✔ DList Methods Implemented

* `insertFront(Object item)`
* `insertBack(Object item)`
* `front()`
* `back()`
* `toString()`

---

## 🧩 Design Decisions

* **Sentinel Head Node**

  * Eliminates special cases for empty lists
  * Simplifies insertion and deletion logic

* **Node Validation**

  * Every operation checks if a node is valid
  * Invalid operations throw `InvalidNodeException`

* **Encapsulation**

  * Node references are managed internally
  * External access is controlled via methods

---

## 📂 Project Structure

```
Re-Implementing-a-doubly-Linked-lists/
│
├── list/
│   ├── List.java
│   ├── ListNode.java
│   ├── DList.java
│   ├── DListNode.java
│   └── InvalidNodeException.java
│
├── Test2.java
└── README.md
```

---

## ▶️ How to Run

1. Compile all Java files:

```bash
javac list/*.java Test2.java
```

2. Run the test program:

```bash
java Test2
```

---

## 🧪 Sample Output

```
[ 1  1.5  2  3  4  5  5.5  6 ]
[ 1.5  2  3  4  5  5.5  6 ]
```

---

## 🏫 Academic Information

* **Course:** Object-Oriented Programming
* **University:** Hubei University of Technology
* **Student Name:** Muntasir Md Fahim (王一然)
* **Student ID:** 1911521213
* **Class:** 19lq CST
* **Date:** December 2021

---

## 📜 License

This project was developed for **academic and educational purposes**.
Free to use for learning and reference with proper attribution.

---

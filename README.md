# Doubly Linked List Implementation (Java)

This repository contains a clean and object-oriented implementation of a **Doubly Linked List** in Java, developed as part of an **Object-Oriented Programming (OOP)** course exercise.

---

## 📌 Project Overview

The goal of this project is to re-implement a doubly linked list by following a given abstract API.
The implementation supports constant-time insertion, deletion, and traversal using a **sentinel (dummy) head node** to simplify edge cases.

---

## ✨ Features

* Doubly linked list with **sentinel head node**
* Insert elements at front and back
* Insert before and after a given node
* Remove nodes safely
* Forward traversal using `toString()`
* Proper exception handling for invalid nodes
* Accurate list size management

---

## 🧠 Design Decisions

* **Sentinel Node**
  A dummy head node is used so that the list is never truly empty.
  This removes the need for special cases when inserting or deleting nodes.

* **Node Validity Checking**
  A node is considered valid only when it belongs to a list (`myList != null`).
  Removed nodes are explicitly invalidated.

* **Encapsulation**
  `DListNode` handles node-level operations (insert, remove).
  `DList` handles list-level responsibilities (size, front, back).

---

## ⏱ Time Complexity

| Operation                  | Complexity |
| -------------------------- | ---------- |
| insertFront / insertBack   | O(1)       |
| insertBefore / insertAfter | O(1)       |
| remove                     | O(1)       |
| traversal                  | O(n)       |

---

## 🛠 How to Compile and Run

```bash
javac list/*.java test/Test2.java
java test.Test2
```

---

## 🧪 Sample Output

```
[ 1 1.5 2 3 4 5 5.5 6 ]
[ 1.5 2 3 4 5 5.5 6 ]
```

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
├── test/
│   └── Test2.java
│
└── README.md
```

---

## 🎓 Course Information

* **Course**: Object-Oriented Programming
* **Institution**: Hubei University of Technology
* **Academic Year**: 2021

---

## ✍ Author

**Md Fahim Muntasir**
Computer Science & Technology

---


Just tell me 👌

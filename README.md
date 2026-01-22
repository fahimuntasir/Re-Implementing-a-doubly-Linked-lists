# Doubly Linked List – Java Implementation

This repository contains a clean, object-oriented implementation of a
**Doubly Linked List** in Java, developed as part of an
**Object-Oriented Programming** course exercise.

## 📘 Overview
The implementation follows a provided abstract API and uses a
**sentinel node design** to simplify insertion and deletion logic.

## ✨ Features
- Sentinel head node
- O(1) insertion and deletion
- Node validity checking
- Exception-safe operations
- Clean separation between list and node responsibilities

## 🧠 Design Highlights
- Sentinel node removes edge cases
- Each node manages its own neighbors
- List size tracked accurately
- Invalid nodes throw exceptions

## 🛠 Compile & Run
```bash
javac list/*.java test/Test2.java
java test.Test2

# concurrent-programming

# 🛒 Concurrent Programming Shop Project

The **Shop Project** is a concurrency-focused Python program that simulates customers and shop assistants operating in a shared environment. It demonstrates **race conditions**, **synchronization primitives** (locks and semaphores), and safe concurrent programming practices.

---

## 📚 Project Overview

This project models:
- Multiple **customer threads** trying to purchase items from a shared inventory.
- **Shop assistants** that restock inventory while customers are buying.
- Scenarios with and without proper synchronization to show the difference between:
  - **UNSAFE mode:** race conditions cause corrupted inventory counts.
  - **SAFE mode:** locks and semaphores ensure thread-safe, consistent results.

---

## 🧠 Concepts Practiced

- **Threading (`threading.Thread`)**
- **Shared resources (dictionary-based inventory)**
- **Race conditions**
- **Synchronization with `threading.Lock`**
- **Limited resources with `threading.Semaphore`**

---

## 📂 File Structure

## run instruction

---

## 🐍 Requirements

- Python 3.9+ recommended  
- No external libraries required (uses only Python standard library)

---

## ▶️ How to Run

Run the main simulation:

```bash
python shop.py

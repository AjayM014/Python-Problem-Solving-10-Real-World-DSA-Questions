# Python Problem Solving – 10 Real-World DSA Questions

This repository contains **10 real-world problem-solving questions implemented in Python**. The problems are designed to improve logical thinking, algorithmic problem-solving, and understanding of commonly used **DSA concepts**.

## 📌 Problems Covered

| No. | Problem                         | Main Concept                  |
| --- | ------------------------------- | ----------------------------- |
| 1   | Student Attendance Analysis     | Sliding Window                |
| 2   | Online Shopping Price Analysis  | Kadane's Algorithm            |
| 3   | Rainwater Collection System     | Two Pointers / Prefix Maximum |
| 4   | Employee Performance Analysis   | Kadane's Algorithm            |
| 5   | Product Sales Analysis          | Dynamic Programming           |
| 6   | Customer Purchase History       | Sliding Window + HashSet      |
| 7   | Bank Transaction Analysis       | Prefix Sum + HashMap          |
| 8   | Employee Skill Grouping         | Hashing / Sorting             |
| 9   | Network Packet Analysis         | HashSet                       |
| 10  | Hospital Appointment Scheduling | Sorting + Interval Merging    |

---

## 📝 Problem Statements

### 1. Student Attendance Analysis

A college maintains the daily attendance details of its students in the form of a list containing student IDs. Some students may have attended multiple sessions on the same day.

The objective is to find the **longest continuous sequence of sessions in which no student ID is repeated**.

**Concept:** Sliding Window

---

### 2. Online Shopping Price Analysis

An online shopping application stores discount values for products viewed during a browsing session.

The objective is to find the **continuous range having the maximum possible total discount value**.

**Concept:** Kadane's Algorithm

---

### 3. Rainwater Collection System

A city has buildings of different heights arranged along a straight road. During rainfall, water can be trapped between taller buildings.

The objective is to calculate the **total amount of rainwater that can be trapped**.

**Concept:** Two Pointers / Prefix Maximum

---

### 4. Employee Performance Analysis

A company stores the monthly performance scores of an employee. The scores may contain both positive and negative values.

The objective is to find the **continuous period with the highest overall performance score**.

**Concept:** Kadane's Algorithm

---

### 5. Product Sales Analysis

A retail company stores daily sales-related values for a product. Some values may be negative because of seasonal adjustments.

The objective is to find the **continuous range having the maximum product**.

**Concept:** Dynamic Programming

---

### 6. Customer Purchase History

An e-commerce application stores product IDs purchased by a customer in chronological order. The same product may appear multiple times.

The objective is to find the **longest consecutive sequence containing only unique product IDs**.

**Concept:** Sliding Window + HashSet

---

### 7. Bank Transaction Analysis

A bank stores transaction amounts for a customer's account.

The objective is to determine **how many continuous groups of transactions have a sum exactly equal to a given target amount**.

**Concept:** Prefix Sum + HashMap

---

### 8. Employee Skill Grouping

A company receives employee skill codes represented as strings. Employees having the same characters in their skill codes belong to the same category, even if the characters appear in a different order.

The objective is to **group strings containing the same characters**.

**Concept:** Hashing / Sorting

---

### 9. Network Packet Analysis

A network monitoring system receives packet identifiers in chronological order.

The objective is to determine the **longest sequence of consecutive numerical identifiers**, regardless of their original order in the input.

**Concept:** HashSet

---

### 10. Hospital Appointment Scheduling

A hospital receives appointment requests represented by starting and ending times. Some appointment periods may overlap.

The objective is to **merge all overlapping appointment intervals** so that the final schedule contains only non-overlapping ranges.

**Concept:** Sorting + Interval Merging

---

## 🎯 Learning Objectives

By solving these problems, you can practice:

* Python lists and strings
* Loops and conditional statements
* Sliding Window technique
* Kadane's Algorithm
* HashSet
* HashMap / Dictionary
* Prefix Sum
* Dynamic Programming
* Sorting
* Two Pointer technique
* Interval merging
* Time and space complexity analysis
* Real-world problem-solving

## 🛠️ Technologies Used

* **Python 3**
* Data Structures
* Algorithms
* Problem Solving

## 📂 Suggested Project Structure

```text
Python-Problem-Solving/
│
├── 01_student_attendance.py
├── 02_online_shopping_discount.py
├── 03_rainwater_collection.py
├── 04_employee_performance.py
├── 05_product_sales.py
├── 06_customer_purchase.py
├── 07_bank_transaction.py
├── 08_employee_skill_grouping.py
├── 09_network_packet.py
├── 10_hospital_appointments.py
│
└── README.md
```

## 🚀 How to Run

Make sure Python 3 is installed on your system.

Run any program using:

```bash
python filename.py
```

Example:

```bash
python 02_online_shopping_discount.py
```

## 📚 Purpose

These problems are created to practice **DSA concepts through real-world scenarios** rather than solving only theoretical problems.

The goal is to understand:

**Problem → Logic → Algorithm → Python Implementation → Output**

---

## 👨‍💻 Author

**Python DSA Practice**

A collection of Python programs created for learning and improving problem-solving skills.

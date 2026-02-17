# 📦 Project 20 — Stack_By_Array Class  
### C++ | OOP | Inheritance | Code Reusability

---

## 📌 Introduction

This project implements a **Stack data structure using a Dynamic Array as the underlying storage mechanism**.

Unlike earlier implementations that relied on Linked Lists or Queue inheritance, this version is built on top of our custom Dynamic Array-based architecture.

The goal of this project is not complexity.

The goal is architectural reuse.

---

## 🎯 Project Objective

- Implement a Stack using a Dynamic Array backend  
- Reuse previously built components  
- Apply Inheritance for behavior extension  
- Strengthen understanding of abstraction and code reuse  

---

## 🧠 Architectural Strategy

This Stack is built using **inheritance from the Queue-by-Array class**.

Instead of writing a Stack from scratch:

- We reused the Queue implementation  
- The Queue itself already depends on `clsDynamicArray`  
- We only adjusted the behavior to match LIFO logic  

That’s it.

No rewriting.
No duplicate logic.
Just smart reuse.

---

## 🔄 How It Works Conceptually

A Stack follows **LIFO (Last In, First Out)**.

To achieve this using the existing Queue-by-Array logic:

- `Push()` inserts at the beginning  
- `Pop()` removes from the beginning  
- `Top()` retrieves the first element  
- `Bottom()` retrieves the last element  

Only minimal adjustments were needed.

The rest of the functionality (Size, Print, Reverse, Update, Insert, Clear, etc.) was inherited directly.

---

## ⚡ What Makes This Project Powerful

The implementation took less than one minute.

Why?

Because the foundation was already solid.

- Dynamic Array was already implemented  
- Queue was already implemented  
- Stack simply reuses and adjusts behavior  

Each new layer becomes easier than the previous one.

That’s exponential productivity.

---

## 🏗 Design Principles Applied

- Inheritance for behavior extension  
- Composition (Queue depends on Dynamic Array)  
- Zero duplication of core logic  
- Reuse over rewriting  
- Interface consistency  

This project is a practical demonstration of:

> Build once. Reuse forever.

---

## 📚 Learning Outcome

This small project reinforces big engineering lessons:

- Strong foundations multiply speed  
- Reusable components reduce future effort  
- Architecture determines productivity  
- Code clarity improves scalability  
- Good design compounds over time  

The first data structure takes time.

The second takes less.

The third takes even less.

Eventually, you become 10–20x faster than someone rewriting everything from scratch.

---

## 🚀 Why These Small Projects Matter

These projects may look small.

But they connect ideas together:

- Dynamic Memory  
- Data Structures  
- OOP  
- Inheritance  
- Composition  
- Clean Architecture  

The real goal is not memorizing solutions.

It’s learning how to connect concepts and apply techniques to any new problem.

---

## 🛠 Technologies Used

- C++  
- Templates  
- Object-Oriented Programming  
- Inheritance  
- Custom Dynamic Array Library  

---

## 🌐 Platform

Programming Advices  
https://programmingadvices.com

---

## 👨‍🏫 Instructor

Dr. Mohammed Abu-Hadhoud  
Founder & Instructor — Programming Advices

---

## 🔥 Final Takeaway

When you increase code reusability…

Productivity increases.

When productivity increases…

Your value increases.

The task that takes someone a week  
can take you hours.

That’s how strong engineers are built.

And this is just another step forward.

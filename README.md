# 🐍 Python Roadmap

This project contains a collection of Python exercises and functions divided into three difficulty levels: **Beginner**, **Intermediate**, and **Advanced**. Each section includes practical examples and implementations designed to help learners progressively master key concepts of the Python language.

---

## 📂 Project Structure

```
python-roadmap/
│
├── beginner/
│   ├── basics.py
│   ├── loops_and_conditions.py
│   └── ...
│
├── intermediate/
│   ├── file_handling.py
│   ├── oop_intro.py
│   └── ...
│
├── advanced/
│   ├── decorators.py
│   ├── async_programming.py
│   └── ...
│
└── README.md
```

---

## 🧩 Difficulty Levels

### 🟢 Beginner
Covers the fundamental building blocks of Python:
- Variables, data types, and operators
- Conditions and loops
- Functions and modules
- Lists, dictionaries, and tuples

**Example:**
```python
def is_even(number):
    """Returns True if the number is even, otherwise False."""
    return number % 2 == 0
```

---

### 🟠 Intermediate
Focuses on practical programming skills and deeper understanding:
- Object-Oriented Programming (OOP)
- File handling and exception management
- Working with external libraries
- Data manipulation (JSON, CSV, etc.)

**Example:**
```python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def greet(self):
        return f"Hi, my name is {self.name} and I'm {self.age} years old."
```

---

### 🔴 Advanced
Covers advanced concepts and optimization techniques:
- Decorators and generators
- Asynchronous programming
- Design patterns
- Testing and performance tuning

**Example:**
```python
import asyncio

async def download_data():
    await asyncio.sleep(1)
    print("Download completed!")

asyncio.run(download_data())
```

---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/python-roadmap.git
   cd python-roadmap
   ```

2. (Optional) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```

3. Run one of the files:
   ```bash
   python beginner/basics.py
   ```

---

## 🧠 Project Goal

The goal of this project is to create a progressive Python roadmap to:
- Strengthen the fundamentals of the language
- Improve understanding of intermediate concepts
- Explore advanced programming techniques

This roadmap serves as a practical learning path for those who want to evolve from beginner to advanced Python developer.

---

## 📜 License

This project is distributed under the **MIT License**. You are free to modify, improve, and share it.

---

✍️ **Author:** Leonardo P.  
🕓 **Last updated:** November 2025


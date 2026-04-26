<div align="center">

# 🔢 Calculator

![Python](https://img.shields.io/badge/Python-3.x-00ff41?style=for-the-badge&logo=python&logoColor=00ff41&labelColor=0d1117)
![Difficulty](https://img.shields.io/badge/Difficulty-Beginner-00ff41?style=for-the-badge&labelColor=0d1117)
![Status](https://img.shields.io/badge/Status-Complete-00ff41?style=for-the-badge&labelColor=0d1117)

> **Project #3 — Two numbers. One operator. Instant result. 🖤**

</div>

---

## 💡 What It Does

```
Enter two numbers.
Pick an operator: + - * /
Get the result instantly.
Wrong operator? It tells you. ❌
```

---

## 🎮 Demo

```bash
> Enter the number 1: 15
> Enter the number 2: 5
> Enter the operator: *
  75

> Enter the number 1: 100
> Enter the number 2: 4
> Enter the operator: /
  25.0
```

---

## ▶️ Run It

```bash
python CALCULATOR.PY
```

---

## ➕ Supported Operations

| Operator | Operation | Example | Result |
|----------|-----------|---------|--------|
| `+` | Addition | 5 + 3 | 8 |
| `-` | Subtraction | 10 - 4 | 6 |
| `*` | Multiplication | 6 * 7 | 42 |
| `/` | Division | 20 / 4 | 5.0 |

---

## 🧠 Concepts Used

| Concept | Purpose |
|---------|---------|
| `int(input())` | Get numbers from user |
| `if / elif / else` | Check which operator was entered |
| Arithmetic operators | Perform the math |

---

## 💻 Source Code

```python
num1 = int(input("Enter the number 1: "))
num2 = int(input("Enter the number 2: "))
operator = input("Enter the operator: ")

if operator == "+":
    print(num1 + num2)
elif operator == "-":
    print(num1 - num2)
elif operator == "*":
    print(num1 * num2)
elif operator == "/":
    print(num1 / num2)
else:
    print("Invalid operator")
```

---

<div align="center">

[🔙 Back to Portfolio](../README.md) • [👤 My Profile](https://github.com/AYDINKHAN)

</div>

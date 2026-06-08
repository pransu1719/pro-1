<div align="center">

# 🐍 Personal Data Collector

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=FFD43B&center=true&vCenter=true&width=500&lines=Interactive+Python+Program;Explore+Variables+%26+Data+Types;Learn+Memory+Addresses+with+id()" alt="Typing SVG" />

<br/>

![Python](https://img.shields.io/badge/Python-3.x-FFD43B?style=for-the-badge&logo=python&logoColor=4B8BBE)
![Level](https://img.shields.io/badge/Level-Beginner-3ddba8?style=for-the-badge&logo=star&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-ff6b9d?style=for-the-badge&logo=checkmarx&logoColor=white)
![Type](https://img.shields.io/badge/Type-Console%20App-a78bfa?style=for-the-badge&logo=terminal&logoColor=white)

<br/>

> 🎯 *A beginner-friendly Python program that collects user data, displays variable types, memory addresses, and calculates birth year!*

</div>

---

## 📸 Program Output Screenshot

<div align="center">

![Program Output](output_screenshot.png)

</div>

---

## 📖 About the Project

This is an **interactive Python console application** that:

- 👤 Collects personal data from the user via `input()`
- 🔢 Converts data into appropriate types using **type casting** (`int()`, `float()`)
- 🧠 Displays each variable's **data type** using `type()`
- 📍 Shows the **memory address** of each variable using `id()`
- 📅 Calculates the user's **approximate birth year**
- 💬 Uses **f-strings** for formatted output

---

## ✨ Features

| Feature | Description |
|---|---|
| ⌨️ **User Input** | Takes name, age, height & favourite number |
| 🔄 **Type Casting** | Converts string input to `int` and `float` |
| 🔍 **Type Checking** | Displays `<class 'str'>`, `<class 'int'>`, `<class 'float'>` |
| 🧠 **Memory Address** | Shows RAM address with `id()` function |
| 📅 **Birth Year Calc** | Estimates birth year from age |
| 💬 **F-String Output** | Modern formatted printing |

---

## 📊 Variables & Data Types

```python
name       = input(...)        # → str   (text)
age        = int(input(...))   # → int   (whole number)
height     = float(input(...)) # → float (decimal number)
fav_number = int(input(...))   # → int   (whole number)
```

| Variable | Example Value | Python Type | Description |
|---|---|---|---|
| `name` | `"pransu"` | `<class 'str'>` | Text / String |
| `age` | `17` | `<class 'int'>` | Whole Number |
| `height` | `65.0` | `<class 'float'>` | Decimal Number |
| `fav_number` | `12` | `<class 'int'>` | Whole Number |

---

## 💻 Source Code

```python
print("welcome to the interactive personal data collector!\n")

# ── Collecting User Input ─────────────────────────────
name       = input("please enter your name:")
age        = int(input("please enter your age:"))
height     = float(input("please enter your height:"))
fav_number = int(input("please enter your favourite number:"))

# ── Birth Year Calculation ────────────────────────────
print(f"your birth year is approximately: {2026 - age} based on your age of {age}")

# ── Display Variable Info ─────────────────────────────
print(f"name:       {name}      (type:{type(name)},  memory address:{id(name)})")
print(f"age:        {age}       (type:{type(age)},   memory address:{id(age)})")
print(f"height:     {height}    (type:{type(height)},memory address:{id(height)})")
print(f"fav_number: {fav_number}(type:{type(fav_number)},memory address:{id(fav_number)})")

print("Thank you for using the personal data collector. Goodbye!")
```

---

## 🚀 How to Run

**Step 1** — Make sure Python is installed:
```bash
python --version
```

**Step 2** — Save the file as `pro_1.py`

**Step 3** — Run the program:
```bash
python pro_1.py
```

**Step 4** — Enter your details when prompted and see the magic! ✨

---

## 🧪 Sample Run

```
welcome to the interactive personal data collector!

please enter your name: pransu
please enter your age: 17
please enter your height: 65
please enter your favourite number: 12

your birth year is approximately: 2009 based on your age of 17

name:pransu      (type:<class 'str'>,   memory address: 2169767288416)
age:17           (type:<class 'int'>,   memory address: 140731174112184)
height:65.0      (type:<class 'float'>, memory address: 2169766614896)
fav_number:12    (type:<class 'int'>,   memory address: 140731174112024)

Thank you for using the personal data collector. Goodbye!
```

---

## 🧠 Python Concepts Learned

```
✅  input()          →  Take user input as string
✅  int()            →  Convert string to integer
✅  float()          →  Convert string to float
✅  type()           →  Check the data type of a variable
✅  id()             →  Get memory address of a variable
✅  f-strings        →  Format strings with variables inline
✅  print()          →  Display output to the console
✅  Type Casting      →  Changing one data type to another
```

---

## 📁 File Structure

```
📂 Project Folder
 ┣ 📄 pro_1.py          ← Main Python program
 ┗ 📄 README.md         ← This file
```

---

<div align="center">

### 🌟 Made with ❤️ by **Pransu**

*Python Learning Journey — Beginner Project #1*

![Python](https://img.shields.io/badge/Keep-Learning-FFD43B?style=flat-square&logo=python&logoColor=4B8BBE)
![Made with Love](https://img.shields.io/badge/Made%20with-❤️-ff6b9d?style=flat-square)

</div>

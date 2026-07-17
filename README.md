# ☕ Wipro Java Full Stack — Learning Journal

<div align="center">

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

**A structured collection of Java programs, logic exercises, and mini-projects built during the Wipro Java Full Stack (JFS) training program.**

[![Repo Size](https://img.shields.io/github/repo-size/albertlivingstan/Wipro_JFS?style=flat-square&color=blueviolet)](https://github.com/albertlivingstan/Wipro_JFS)
[![Last Commit](https://img.shields.io/github/last-commit/albertlivingstan/Wipro_JFS?style=flat-square&color=brightgreen)](https://github.com/albertlivingstan/Wipro_JFS/commits/main)
[![Files](https://img.shields.io/badge/Java%20Files-31-blue?style=flat-square)](https://github.com/albertlivingstan/Wipro_JFS)

</div>

---

## 📌 Table of Contents

- [📁 Project Structure](#-project-structure)
- [🧠 Logic Building](#-logic-building)
  - [Level 1 — Basics](#-level-1--basics)
  - [Level 2 — Number Operations](#-level-2--number-operations)
  - [Level 3 — Patterns & Arrays](#-level-3--patterns--arrays)
  - [Level 4 — Strings & Methods](#-level-4--strings--methods)
  - [Level 5 — Advanced Logic](#-level-5--advanced-logic)
- [🚀 Mini Projects](#-mini-projects)
  - [Java Fundamentals — Employee Payroll](#-java-fundamentals--employee-payroll)
  - [Inheritance — Video Store](#-inheritance--video-store)
- [⚙️ How to Run](#️-how-to-run)
- [👤 Author](#-author)

---

## 📁 Project Structure

```
Wipro_JFS/
│
├── 🧠 LogicBuilding/
│   ├── L1/   ← Variables, Conditions & Loops
│   ├── L2/   ← Number Operations & Counting
│   ├── L3/   ← Patterns & Arrays
│   ├── L4/   ← Strings & Methods
│   └── L5/   ← Advanced Logic
│
└── 🚀 Mini_Projects/
    ├── Java_Fundamentals/   ← Employee Payroll System
    └── Inheritance/         ← Video Store Management
```

---

## 🧠 Logic Building

> Progressively challenging Java exercises across 5 levels to build strong programming fundamentals.

---

### 🟢 Level 1 — Basics

> **Focus:** Variables, conditional statements, basic I/O, and simple loops.

<details>
<summary><b>📄 A1.java — Cyclic Rotation of 3 Variables</b></summary>

**Problem:** Given three integers `a`, `b`, `c`, cyclically rotate them such that:
- `a → b`, `b → c`, `c → a`

**Concepts:** Variables, temp swapping, Scanner input

```java
int temp = a;
a = c;
c = b;
b = temp;
```

🔗 [View Source](LogicBuilding/L1/A1.java)

</details>

<details>
<summary><b>📄 A2.java — Count Students Who Passed</b></summary>

**Problem:** Read marks of 3 students and count how many scored ≥ 35 (passing marks).

**Concepts:** `for` loop, `if` condition, counter variable

```java
if (mark >= 35) count++;
```

🔗 [View Source](LogicBuilding/L1/A2.java)

</details>

<details>
<summary><b>📄 A3.java — Assignment 3</b></summary>

🔗 [View Source](LogicBuilding/L1/A3.java)

</details>

<details>
<summary><b>📄 A4.java — Assignment 4</b></summary>

🔗 [View Source](LogicBuilding/L1/A4.java)

</details>

<details>
<summary><b>📄 A5.java — Assignment 5</b></summary>

🔗 [View Source](LogicBuilding/L1/A5.java)

</details>

---

### 🟡 Level 2 — Number Operations

> **Focus:** While loops, digit manipulation, mathematical computations.

<details>
<summary><b>📄 A1.java — Count Digits in a Number</b></summary>

**Problem:** Given a number, count the total number of digits in it.

**Concepts:** `while` loop, integer division

```java
while (num > 0) {
    count++;
    num = num / 10;
}
```

🔗 [View Source](LogicBuilding/L2/A1.java)

</details>

<details>
<summary><b>📄 A2.java — Assignment 2</b></summary>

🔗 [View Source](LogicBuilding/L2/A2.java)

</details>

<details>
<summary><b>📄 A3.java — Assignment 3</b></summary>

🔗 [View Source](LogicBuilding/L2/A3.java)

</details>

<details>
<summary><b>📄 A4.java — Assignment 4</b></summary>

🔗 [View Source](LogicBuilding/L2/A4.java)

</details>

<details>
<summary><b>📄 A5.java — Assignment 5</b></summary>

🔗 [View Source](LogicBuilding/L2/A5.java)

</details>

---

### 🟠 Level 3 — Patterns & Arrays

> **Focus:** Nested loops, array manipulation, pattern printing.

| File | 🔗 Source |
|------|-----------|
| A1.java | [View](LogicBuilding/L3/A1.java) |
| A2.java | [View](LogicBuilding/L3/A2.java) |
| A3.java | [View](LogicBuilding/L3/A3.java) |
| A4.java | [View](LogicBuilding/L3/A4.java) |

---

### 🔴 Level 4 — Strings & Methods

> **Focus:** String operations, method creation, and modular programming.

| File | 🔗 Source |
|------|-----------|
| A1.java | [View](LogicBuilding/L4/A1.java) |
| A2.java | [View](LogicBuilding/L4/A2.java) |
| A3.java | [View](LogicBuilding/L4/A3.java) |
| A4.java | [View](LogicBuilding/L4/A4.java) |
| A5.java | [View](LogicBuilding/L4/A5.java) |

---

### 🟣 Level 5 — Advanced Logic

> **Focus:** Complex problem solving, algorithms, and OOP concepts.

| File | 🔗 Source |
|------|-----------|
| A1.java | [View](LogicBuilding/L5/A1.java) |
| A2.java | [View](LogicBuilding/L5/A2.java) |
| A3.java | [View](LogicBuilding/L5/A3.java) |
| A4.java | [View](LogicBuilding/L5/A4.java) |
| A5.java | [View](LogicBuilding/L5/A5.java) |

---

## 🚀 Mini Projects

---

### 💼 Java Fundamentals — Employee Payroll

> 📂 `Mini_Projects/Java_Fundamentals/`

<details>
<summary><b>📋 Project Overview</b></summary>

A command-line **Employee Payroll System** that looks up an employee by their ID and generates a formatted salary slip.

**Features:**
- 🔍 Employee lookup by ID (1001–1007)
- 📊 Salary computation: `Basic + HRA + DA - IT`
- 🏷️ Designation mapping via character codes
- 🖨️ Formatted tabular output using `printf`

**Employees Supported:**

| Emp No | Name    | Department    | Designation  |
|--------|---------|---------------|--------------|
| 1001   | Ashish  | R&D           | Engineer     |
| 1002   | Sushma  | PM            | Consultant   |
| 1003   | Rahul   | Acct          | Clerk        |
| 1004   | Chahat  | Front Desk    | Receptionist |
| 1005   | Ranjan  | Engg          | Manager      |
| 1006   | Suman   | Manufacturing | Engineer     |
| 1007   | Tanmay  | PM            | Consultant   |

**Salary Formula:**

```
Net Salary = Basic + HRA + DA - Income Tax
```

**How to Run:**
```bash
javac Java_Fundamentals/Project1.java
java Java_Fundamentals.Project1 1001
```

</details>

🔗 [View Source](Mini_Projects/Java_Fundamentals/Project1.java)

---

### 🎬 Inheritance — Video Store Management

> 📂 `Mini_Projects/Inheritance/`

<details>
<summary><b>📋 Project Overview</b></summary>

A **Video Store Management System** built using core OOP principles — encapsulation and class composition.

**Classes:**

| Class | Role |
|-------|------|
| `Video.java` | Represents a single video with name, checkout status & rating |
| `VideoStore.java` | Manages a collection of up to 100 videos |
| `VideoLauncher.java` | Entry point — runs the store demo |

**Features:**
- ➕ Add videos to the store
- 📤 Check out a video
- 📥 Return a video
- ⭐ Rate a video (1–5)
- 📋 List all inventory with status & ratings

**Key OOP Concepts Demonstrated:**
- 🔒 **Encapsulation** — private fields with public getters/setters
- 🏗️ **Object Composition** — `VideoStore` contains an array of `Video` objects
- 📦 **Packages** — organized under the `Inheritance` package

**Sample Output:**
```
----------------------------------------------
Video Name           Checkout Status    Rating
----------------------------------------------
Inception            true               5
Interstellar         false              4
----------------------------------------------
```

**How to Run:**
```bash
javac Inheritance/*.java
java Inheritance.VideoLauncher
```

</details>

🔗 [View Source — Video.java](Mini_Projects/Inheritance/Video.java) | [VideoStore.java](Mini_Projects/Inheritance/VideoStore.java) | [VideoLauncher.java](Mini_Projects/Inheritance/VideoLauncher.java)

---

## ⚙️ How to Run

### Prerequisites
- ✅ Java JDK 8 or above installed
- ✅ IntelliJ IDEA (recommended) or any Java IDE
- ✅ Git

### Clone the Repository
```bash
git clone https://github.com/albertlivingstan/Wipro_JFS.git
cd Wipro_JFS
```

### Run a Logic Building Exercise
```bash
# Example: Run L1/A1.java
cd LogicBuilding
javac L1/A1.java
java L1.A1
```

### Run a Mini Project
```bash
# Employee Payroll (pass employee ID as argument)
cd Mini_Projects
javac Java_Fundamentals/Project1.java
java Java_Fundamentals.Project1 1003

# Video Store
javac Inheritance/*.java
java Inheritance.VideoLauncher
```

---

## 👤 Author

<div align="center">

**Albert Livingstan**

[![GitHub](https://img.shields.io/badge/GitHub-albertlivingstan-181717?style=for-the-badge&logo=github)](https://github.com/albertlivingstan)

*Wipro Java Full Stack Training — 2026*

</div>

---

<div align="center">

⭐ *If you find this helpful, drop a star on the repo!* ⭐

</div>

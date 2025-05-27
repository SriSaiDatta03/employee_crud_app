# 🧑‍💼 Employee CRUD App (Tkinter + MySQL)

A lightweight desktop-based **Employee Management System** built using **Python (Tkinter)** and **MySQL**. This GUI application allows you to perform essential CRUD (Create, Read, Update, Delete) operations on employee records in real time.

## 🚀 Features

- ✅ Add new employee records
- 🔍 Fetch employee details by ID
- ✏️ Update employee information
- 🗑️ Delete employee records
- 📋 Display all employee data
- 🔄 Reset form fields
- 🔔 Real-time alerts using message boxes


## 🛠️ Tech Stack

| Technology           | Purpose                        |
|----------------------|---------------------------------|
| 🐍 Python            | Core programming language       |
| 🖼️ Tkinter           | GUI toolkit for desktop apps    |
| 🐬 MySQL             | Relational database             |
| `mysql-connector`   | Python-to-MySQL interface       |


## 🧱 Database Schema

Run the following SQL commands to set up your database:

```sql
CREATE DATABASE employee;

USE employee;

CREATE TABLE empDetails (
    empId VARCHAR(10) PRIMARY KEY,
    empName VARCHAR(50),
    empDept VARCHAR(50)
);
````

---

## 📦 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/coding-pythonx/employee-crud-app.git
cd employee-crud-app
```

### 2. Install dependencies

```bash
pip install mysql-connector-python
```

### 3. Update MySQL credentials

In `main.py`, replace `YOUR_PASSWORD` with your actual MySQL root password:

```python
myDB = mysql.connector.connect(
    host="localhost", user="root", passwd="YOUR_PASSWORD", database="employee")
```

### 4. Run the app

```bash
python main.py
```

---

## 🖥️ User Interface

![Employee_CRUD](https://github.com/user-attachments/assets/4543df0f-023d-4c5a-894d-cf17bbcb33b8)


* **Simple and intuitive layout**
* **Responsive feedback on user actions**
* **Clean display of employee records**

---

## 💼 Why This Project?

This application demonstrates my ability to:

* Build real-world desktop apps with GUI in Python
* Integrate front-end and database layers
* Apply clean coding principles
* Implement user feedback and data validation logic

I built this project to sharpen my skills in **full-stack Python development** and provide a simple yet functional HR management tool.

---

## ⭐ Like This Project?

If you found this useful or interesting, please give it a ⭐ on GitHub and consider sharing it with others. It helps a lot!

---

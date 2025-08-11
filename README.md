# Django
Dango — A step-by-step Django learning and starter project to build web applications from scratch.

````markdown
# 🚀 Django Project Setup Guide

This repository contains the basic setup steps to start a **Django project** from scratch using a virtual environment.

---

## 📌 Prerequisites
Make sure you have the following installed on your system:
- **Python 3.x** → [Download Here](https://www.python.org/downloads/)
- **pip** (comes with Python)
- **Virtual Environment** module (`venv`)

---

## 🛠 Step-by-Step Setup

### **1️⃣ Create a Virtual Environment**
```bash
python -m venv env
````

This will create a folder named `env` containing the virtual environment.

---

### **2️⃣ Activate the Virtual Environment**

* **Windows (CMD)**:

```bash
env\Scripts\activate
```

* **Windows (PowerShell)**:

```bash
.\env\Scripts\Activate.ps1
```

* **macOS/Linux**:

```bash
source env/bin/activate
```

✅ After activation, your terminal will show `(env)` at the beginning.

---

### **3️⃣ Install Django**

```bash
pip install django
```

---

### **4️⃣ Create a New Django Project**

```bash
django-admin startproject myproject
```

Replace `myproject` with your preferred project name.

---

### **5️⃣ Run the Development Server**

```bash
cd myproject
python manage.py runserver
```

🌐 Visit **`http://127.0.0.1:8000/`** in your browser to see the default Django welcome page.

---

## 📜 Quick Command Reference

| Step                       | Command                               |
| -------------------------- | ------------------------------------- |
| Create Virtual Env         | `python -m venv env`                  |
| Activate Env (Windows)     | `env\Scripts\activate`                |
| Activate Env (macOS/Linux) | `source env/bin/activate`             |
| Install Django             | `pip install django`                  |
| Create Project             | `django-admin startproject myproject` |
| Run Server                 | `python manage.py runserver`          |

---

## 📂 Folder Structure After Setup

```
myproject/
│
├── manage.py
├── myproject/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── env/
```

---

## 📢 Notes

* Always **activate your virtual environment** before running any Django commands.
* Use `pip freeze > requirements.txt` to save dependencies for future installations.
* Deactivate the virtual environment with:

```bash
deactivate
```

---

💡 *Happy Coding!* 🚀

```

---

I’ve designed it with **GitHub markdown styling**, emojis, tables, and code blocks so it looks professional when viewed on GitHub.  

If you want, I can also **add a "Run This Project" section** so that anyone cloning your repo can start it instantly. That will make your README even better for GitHub.
```

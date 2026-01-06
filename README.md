
# 📚 SkillSphere – Learning Management System (LMS)

SkillSphere is a **full-stack Learning Management System (LMS)** developed using **Python and Django**.
The platform is designed to manage online learning efficiently by providing role-based access for **Admins, Instructors, and Students**, enabling course management, content delivery, and user interaction in a structured environment.

This project demonstrates strong fundamentals in **backend development, database design, authentication, and MVC architecture**, making it suitable for academic submission and professional portfolios.

---

## 🚀 Key Features

* 🔐 Secure user authentication and authorization
* 👤 Role-based access (Admin, Instructor, Student)
* 📘 Course creation and management
* 📂 Upload and manage learning materials
* 🧑‍🎓 Student enrollment and tracking
* 📊 Dashboard views for different roles
* 🗂️ Structured backend using Django framework

---

## 🛠️ Tech Stack

| Layer           | Technology                  |
| --------------- | --------------------------- |
| Backend         | Python, Django              |
| Database        | MySQL / SQLite              |
| Frontend        | HTML, CSS, Django Templates |
| Authentication  | Django Auth                 |
| Version Control | Git, GitHub                 |

---

## 📁 Project Structure

```
SkillSphere-LMS-portal/
│
├── manage.py
├── skill_sphere_lms/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── apps/
│   ├── users/
│   ├── courses/
│   ├── dashboard/
│
├── templates/
│   ├── base.html
│   ├── login.html
│   └── dashboard.html
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

Follow the steps below to run the project locally.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Sajun28/SkillSphere-LMS-portal.git
cd SkillSphere-LMS-portal
```

---

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

**Activate Virtual Environment**

* Windows:

```bash
venv\Scripts\activate
```

* Linux / macOS:

```bash
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Configure Database

Edit `settings.py`:

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',  # or sqlite3
        'NAME': 'skillsphere_db',
        'USER': 'root',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```

---

### 5️⃣ Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

---

### 6️⃣ Create Superuser (Admin)

```bash
python manage.py createsuperuser
```

---

### 7️⃣ Run the Server

```bash
python manage.py runserver
```

Open browser and visit:
👉 **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**

---

## 👥 User Roles & Access

### 🔑 Admin

* Manage users and roles
* Create and manage courses
* Monitor system activity

### 🎓 Instructor

* Upload course materials
* Manage assigned courses

### 🧑‍🎓 Student

* Enroll in courses
* Access learning content

---

## 🎯 Project Objectives

* To build a real-world **Learning Management System**
* To apply **Django MVC architecture**
* To implement **secure authentication**
* To gain hands-on experience in **full-stack development**

---

## 📌 Use Cases

* Colleges & universities
* Training institutes
* Online skill development platforms
* Corporate learning portals

---

## 🔮 Future Enhancements

* ✅ Online assessments and quizzes
* ✅ Certificate generation
* ✅ Progress analytics & reports
* ✅ REST API integration
* ✅ Responsive UI improvements

---

## 🤝 Contribution Guidelines

Contributions are welcome!
To contribute:

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Submit a Pull Request

---

## 📄 License

This project is developed for **educational purposes**.
You may add an open-source license (MIT / Apache / GPL) if required.

---

## 👨‍💻 Author

**Sajun28**
GitHub: [https://github.com/Sajun28](https://github.com/Sajun28)

---

⭐ If you like this project, don’t forget to **star the repository**!


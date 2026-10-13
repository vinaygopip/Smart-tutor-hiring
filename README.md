# Smart Tutor Hiring System

## 📌 Project Overview

The **Smart Tutor Hiring System** is a web-based application developed using Python and Django that connects students with suitable tutors. It provides a platform where students can register, manage their profiles, and find tutors, while tutors can register and maintain their professional profiles.

The system aims to simplify the tutor hiring process by providing an organized platform for students and tutors.

## 🎯 Objectives

- To provide an online platform for tutor hiring.
- To allow students and tutors to register and log in.
- To maintain student and tutor profiles.
- To simplify communication and tutor discovery.
- To provide separate dashboards for students and tutors.
- To make tutor-related information easy to manage.

## ✨ Features

- Student registration and login
- Tutor registration and login
- Student profile management
- Tutor profile management
- Student dashboard
- Tutor dashboard
- Django authentication
- Database management
- Responsive web interface using HTML and CSS

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Django | Backend web framework |
| HTML | Web page structure |
| CSS | User interface styling |
| SQLite | Database |
| Git | Version control |
| GitHub | Source code hosting |

## 🔄 Project Workflow

1. The user opens the Smart Tutor Hiring website.
2. The user registers as a student or tutor.
3. The user logs in using their credentials.
4. Students access their dashboard and manage their profile.
5. Tutors access their dashboard and manage their professional profile.
6. The application stores and retrieves information from the database.

## 📂 Project Structure

```text
tutor_hiring/
│
├── main/
│   ├── migrations/
│   ├── templates/
│   │   ├── main/
│   │   └── registration/
│   ├── admin.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── static/
│   └── css/
│       └── styles.css
│
├── tutor_hiring/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── manage.py
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/vinaygopip/Smart-tutor-hiring.git
cd Smart-tutor-hiring
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

For Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 4. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 5. Apply Database Migrations

```bash
python manage.py migrate
```

### 6. Start the Development Server

```bash
python manage.py runserver
```

### 7. Open the Application

Visit the following address in your browser:

```text
http://127.0.0.1:8000/
```

## 🧪 Testing

Run Django's system checks:

```bash
python manage.py check
```

Run the application's tests:

```bash
python manage.py test
```

## 🔮 Future Enhancements

- Advanced tutor search and filtering
- Subject-wise tutor recommendations
- Tutor ratings and reviews
- Online booking and scheduling
- Messaging between students and tutors
- Online payment integration
- Email notifications
- Admin analytics dashboard

## 👨‍💻 Author

**Vinay Gopi**

GitHub: [@vinaygopip](https://github.com/vinaygopip)

## ⚠️ Disclaimer

This project is developed for educational and demonstration purposes. Features described in this README should be verified against the implemented application.


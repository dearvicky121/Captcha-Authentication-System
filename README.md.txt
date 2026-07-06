# CAPTCHA-Based Authentication System

## Final Year Project

### Project Overview

This project is a Flask-based web application that provides secure user authentication using an image-based CAPTCHA system.

Unlike traditional text CAPTCHAs, this system generates an image containing multiple objects. The user must count the objects correctly to complete the login or registration process.

The application stores user information securely using password hashing and maintains login history in JSON format.

---

## Features

- User Registration
- User Login
- Object Counting CAPTCHA
- Password Hashing
- Session Management
- Login History
- JSON File Storage
- Responsive Web Interface

---

## Technologies Used

- Python 3
- Flask
- HTML5
- CSS3
- JavaScript
- Pillow (PIL)
- Werkzeug

---

## Folder Structure

```
CAPTCHA-Based-Authentication-System/
│
├── app.py
├── captcha_generator.py
├── assets/
├── static/
├── templates/
├── user_data/
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Installation

Install the required libraries

```bash
pip install -r requirements.txt
```

Run the project

```bash
python app.py
```

Open

```
http://127.0.0.1:5000
```

---

## Future Enhancements

- Database Integration (MySQL)
- Email Verification
- OTP Authentication
- Admin Dashboard
- CAPTCHA Difficulty Levels

---

## Author

**Khaja Nurudin**

B.Tech Final Year Project
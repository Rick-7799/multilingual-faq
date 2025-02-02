# 🌍 Multilingual FAQ Manager 

*A Django-powered platform to manage FAQs with real-time translations and performance optimizations.*

---

## ✨ Why This Project?

- **Language barriers**: Users often need FAQs in their native tongue.
- **Performance**: Slow translations degrade user experience.
- **Simplicity**: Admins deserve a clean interface to manage content.

---

## 🚀 Key Features

- **Dynamic Translations**: Supports Hindi, Bengali, English (expandable).
- **WYSIWYG Editor**: Rich text formatting without coding.
- **Blazing-Fast API**: <100ms response times with Redis caching.
- **Scalable**: Ready for production traffic with Docker and PostgreSQL.

---

## 🛠️ Setup Guide

1. **Download the ZIP File**:
   - Click on the green "Code" button and select "Download ZIP".
   - Extract the contents to your local machine.

2. **Create a Virtual Environment**:
 ``` 
cd path/to/extracted-folder
python -m venv venv
 ```

4. **Activate the Virtual Environment**:
- On Windows:
  ```
  venv\Scripts\activate
  ```
- On macOS/Linux:
  ```
  source venv/bin/activate
  ```


4. **Run Database Migrations**:
 ```
python manage.py migrate
 ```

5. **Create a Superuser (Admin Account)**:
 ```
python manage.py createsuperuser
 ```

6. **Run the Development Server**:
 ```
python manage.py runserver
 ```





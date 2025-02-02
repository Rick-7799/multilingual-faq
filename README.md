text
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
cd path/to/extracted-folder
python -m venv venv
text

3. **Activate the Virtual Environment**:
- On Windows:
  ```
  venv\Scripts\activate
  ```
- On macOS/Linux:
  ```
  source venv/bin/activate
  ```

4. **Install Required Packages**:
pip install -r requirements.txt
text

5. **Run Database Migrations**:
python manage.py migrate
text

6. **Create a Superuser (Admin Account)**:
python manage.py createsuperuser
text

7. **Run the Development Server**:
python manage.py runserver
text

8. **Open your browser and go to** `http://localhost:8000/admin` to start adding FAQs!

---

## 📚 API Examples

Get English FAQs (default)
curl http://localhost:8000/api/faqs/
Get Hindi FAQs
curl http://localhost:8000/api/faqs/?lang=hi
Response Structure
{
"question": "आपका प्रश्न यहाँ...",
"answer": "<p>Your formatted answer...</p>"
}
text

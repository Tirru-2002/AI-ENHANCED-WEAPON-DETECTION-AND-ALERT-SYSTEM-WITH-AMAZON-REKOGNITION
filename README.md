# AI-Enhanced Weapon Detection and Alert System with Amazon Rekognition

This is a **Django-based web application** that integrates **Amazon Rekognition** to detect weapons in images and videos.  
It provides **real-time analysis, user authentication, and a dashboard** for managing and viewing results.

---

## 🚀 Features
- 🔫 Weapon detection in images and videos using **Amazon Rekognition**.  
- 👤 User registration, login, and profile management.  
- 📊 Dashboard for viewing analysis results.  
- 🔐 Secure handling of AWS credentials.  

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Tirru-2002/AI-ENHANCED-WEAPON-DETECTION-AND-ALERT-SYSTEM-WITH-AMAZON-REKOGNITION.git
cd AI-ENHANCED-WEAPON-DETECTION-AND-ALERT-SYSTEM-WITH-AMAZON-REKOGNITION
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate   # On Mac/Linux
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Setup AWS Keys and Django SECRET_KEY
```bash
cd weapon_detection\settings.py
```
#### AWS Credentials
```env
AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret_key
AWS_REGION=your_region
```

#### Django Secret Key
- SECRET_KEY=your_generated_secret_key
```bash
python -c "from django.core.management.utils import get_random_secret_key; print(get_random_secret_key())"
```

### 5️⃣ Run Migrations

```bash
python manage.py migrate
```

### 6️⃣ Start Development Server

```bash
python manage.py runserver
```

---
📌 Usage

- Register or log in to the application.
- Upload an image or video for weapon detection.
- View results in the dashboard.
- Get instant alerts when a weapon is detected.
---
---
🛠️ Tech Stack

- Backend: Django, Python
- Frontend: HTML, CSS, JavaScript (Django templates)
- Cloud: AWS Rekognition, AWS S3
- Database: SQLite (default) / PostgreSQL
---


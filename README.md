# 🚀 Kas Management

A management system developed with Django, designed to handle information in a structured, scalable, and secure way. The project follows backend best practices and is prepared to evolve into a microservices architecture.

## 📌 Description

Kas Management is a backend application built with Django that allows managing system entities through a robust and well-organized API. The project is designed to scale, integrate with mobile applications or modern frontends, and be deployed in cloud environments such as AWS.

## 🏗 Architecture

- **Framework:** Django 
- **Base de datos:** PostgreSQL 
- **Arquitectura:** Monolito modular (preparado para migración a microservicios) 
- **API:** Django REST Framework 
- **Despliegue:** AWS EC2 (planeado) 
- **Base de datos remota:** AWS RDS (planeado)

## ⚙️ Installation and Setup
### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/kas-management.git
cd kas-management
```
### 2️⃣ Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Configure environment variables
Create a .env file with:
```bash
DEBUG=True
SECRET_KEY=your_secret_key
DATABASE_NAME=kas_db
DATABASE_USER=postgres
DATABASE_PASSWORD=your_password
DATABASE_HOST=localhost
DATABASE_PORT=5432
```
### 5️⃣ Apply migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 6️⃣ Run the server
```bash
python manage.py runserver
```

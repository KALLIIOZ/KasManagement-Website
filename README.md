# 🚀 Kas Management

Sistema de gestión desarrollado con **Django**, diseñado para administrar información de manera estructurada, escalable y segura. El proyecto está enfocado en buenas prácticas de arquitectura backend y preparado para evolucionar hacia una arquitectura de microservicios.

---

## 📌 Descripción

Kas Management es una aplicación backend construida con Django que permite gestionar entidades del sistema mediante una API robusta y organizada. El proyecto está pensado para escalar, integrarse con aplicaciones móviles o frontend moderno, y desplegarse en entornos cloud como AWS.

---

## 🏗 Arquitectura

- **Framework:** Django  
- **Base de datos:** PostgreSQL  
- **Arquitectura:** Monolito modular (preparado para migración a microservicios)  
- **API:** Django REST Framework  
- **Despliegue:** AWS EC2 (planeado)  
- **Base de datos remota:** AWS RDS (planeado)

---

## ⚙️ Instalación y configuración

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/tuusuario/kas-management.git
cd kas-management

### 2️⃣ Crear entorno virtual
```bash
git clone https://github.com/tuusuario/kas-management.git
cd kas-management

### 2️⃣ Crear entorno virtual
```bash
git clone https://github.com/tuusuario/kas-management.git
cd kas-management

### 2️⃣ Crear entorno virtual
```bash
git clone https://github.com/tuusuario/kas-management.git
cd kas-management
```

### 2️⃣ Crear entorno virtual
```bash
git clone https://github.com/tuusuario/kas-management.git
cd kas-management
```

### 2️⃣ Crear entorno virtual
```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
```

### 3️⃣ Instalar dependencias
```bash
pip install -r requirements.txt
```

### 4️⃣ Configurar variables de entorno
Crea un archivo .env con:

```bash
DEBUG=True
SECRET_KEY=your_secret_key
DATABASE_NAME=kas_db
DATABASE_USER=postgres
DATABASE_PASSWORD=your_password
DATABASE_HOST=localhost
DATABASE_PORT=5432
```

### 5️⃣ Aplicar migraciones
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Aplicar migraciones
```bash
python manage.py makemigrations
python manage.py migrate
```

### 6️⃣ Ejecutar el servidor
```bash
python manage.py runserver
```

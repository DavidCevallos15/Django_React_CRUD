# Proyecto Full Stack CRUD (Django + React)

Este es un proyecto base para construir aplicaciones web modernas, implementando un CRUD (Crear, Leer, Actualizar, Eliminar) completo.

La estructura está dividida en dos componentes principales:
* `/backend`: Una API RESTful construida con Django y Django REST Framework.
* `/frontend`: Una aplicación de una sola página (SPA) construida con React.

---

## 🚀 Tecnologías Utilizadas

### Backend (API REST)

* **Python 3:** Lenguaje principal.
* **Django:** El framework web principal para un desarrollo rápido y seguro.
* **Django REST Framework (DRF):** La mejor herramienta para construir APIs potentes sobre Django.
* **Django CORS Headers:** Para gestionar la comunicación (CORS) y permitir que el frontend se conecte a la API.
* **SQLite3 / MySQL:** Configurado inicialmente con SQLite para facilidad de desarrollo, pero listo para migrar a MySQL o PostgreSQL.

### Frontend (Cliente)

* **React:** Biblioteca JavaScript para construir interfaces de usuario interactivas.
* **Node.js / npm:** Entorno de ejecución y gestión de paquetes.
* **Axios:** Cliente HTTP basado en promesas para consumir la API REST desde el frontend.
* **CSS Básico:** 

---

## 🏁 Cómo Empezar

Para correr este proyecto localmente:

### 1. Backend

```bash
# Entrar al directorio del backend
cd backend

# Activar el entorno virtual (Windows)
.\venv\Scripts\activate

# Correr el servidor
python manage.py runserver

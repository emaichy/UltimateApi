#UltimateApi - Backend

Este repositorio contiene el desarrollo del API REST del proyecto Sistema de Basura Inteligente. Creado con Python y Flask, permite la gestión de usuarios, autenticación y manejo de información del sistema.

Tecnologías utilizadas
- Python 3
- Flask
- MySQL (AWS RDS)
- JWT para autenticación
- SQLAlchemy
- Flask-Migrate
- Flask-CORS

Instalación y ejecución
1. Clonar el repositorio:
git clone https://github.com/emaichy/UltimateApi.git

2. Crear entorno virtual:
python -m venv venv
source venv/bin/activate  # (Linux/Mac)
venv\Scripts\activate     # (Windows)

3. Instalar dependencias:
pip install -r requirements.txt

4. Ejecutar el proyecto:
python app.py

Rutas principales
| Método | Ruta        | Descripción                      |
|--------|-------------|---------------------------------|
| POST   | /login      | Login de usuarios               |
| GET    | /users      | Obtener lista de usuarios       |
| POST   | /users      | Crear usuario                   |
| PUT    | /users/{id} | Actualizar usuario              |
| DELETE | /users/{id} | Eliminar usuario                |

Arquitectura
UltimateApi/
│── app.py           → Archivo principal
│── config.py        → Configuraciones
│── models/          → Modelos de base de datos
│── controllers/     → Lógica de negocio
│── routes/          → Definición de endpoints
│── migrations/      → Migraciones con Flask-Migrate
│── requirements.txt

Autor
- Eduardo Montoya Álvarez

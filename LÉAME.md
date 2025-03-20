Descripción 
Este proyecto es un ejemplo práctico de cómo implementar autenticación de usuarios usando Flask-Login en una aplicación Flask. 
Incluye un sistema de inicio de sesión, protección de rutas y diseño estilizado con Tailwind CSS y Flowbite.

Instalación: 

Clona el repositorio:
git clone https://github.com/TuUsuario/partial3_TuApellido.git

Navega al directorio del proyecto:
cd partial3_TuApellido

Crea un entorno virtual:
python3 -m venv venv

Activa el entorno virtual:
En Windows: .\venv\Scripts\activate
En Mac/Linux: source venv/bin/activate

Instala las dependencias:
pip install -r requirements.txt

Requisitos
Este proyecto usa:

Flask
Flask-Login
Flask-SQLAlchemy
Tailwind CSS (vía CDN)
Flowbite (vía CDN)


Uso
Página de Inicio de Sesión:
Ingresa un nombre de usuario y contraseña válidos para iniciar sesión.
Rutas Protegidas:
Sólo los usuarios autenticados pueden acceder a ciertas páginas (ej. /alumnos).
Cerrar Sesión:
La opción de cerrar sesión está disponible en las páginas protegidas.


Datos adicionales:
Crea una base de datos con el nombre examen en MySQL Worbench


# Memory Album Project

Este proyecto es una aplicación web de álbum de recuerdos construida con Django. Permite a los usuarios registrarse, iniciar sesión, gestionar sus perfiles y subir, editar y eliminar recuerdos. La aplicación está diseñada para ser intuitiva y fácil de usar, proporcionando una experiencia agradable para los usuarios que desean conservar sus recuerdos.

## Características

- **Registro e inicio de sesión de usuarios**: Los usuarios pueden crear una cuenta y acceder a su perfil.
- **Gestión de perfiles de usuario**: Cada usuario tiene un perfil donde puede ver y gestionar sus recuerdos.
- **Subida de recuerdos**: Los usuarios pueden subir recuerdos en forma de imágenes y descripciones.
- **Edición y eliminación de recuerdos**: Los usuarios pueden editar o eliminar sus recuerdos existentes.
- **Página principal**: Muestra los recuerdos más recientes de todos los usuarios.

## Estructura del Proyecto

```
memory_album_project
├── memory_album
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── memory_album_project
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── static
│   ├── css
│   │   └── styles.css
│   ├── js
│   │   └── scripts.js
│   └── images
├── templates
│   ├── base.html
│   ├── home.html
│   ├── login.html
│   ├── profile.html
│   └── register.html
├── manage.py
└── README.md
```

## Instalación

1. Clona el repositorio:
   ```
   git clone <URL_DEL_REPOSITORIO>
   cd memory_album_project
   ```

2. Crea un entorno virtual y actívalo:
   ```
   python -m venv venv
   source venv/bin/activate  # En Windows usa `venv\Scripts\activate`
   ```

3. Instala las dependencias:
   ```
   pip install -r requirements.txt
   ```

4. Realiza las migraciones:
   ```
   python manage.py migrate
   ```

5. Ejecuta el servidor de desarrollo:
   ```
   python manage.py runserver
   ```

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor abre un issue o envía un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT.
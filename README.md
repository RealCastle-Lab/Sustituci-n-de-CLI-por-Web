# Aplicación Web de Gestión de Datos de Vacunación con Flask y Redis

## Descripción del Proyecto
Este proyecto es una aplicación web desarrollada utilizando Flask, diseñada para reemplazar una aplicación de línea de comandos preexistente. La aplicación permite visualizar y gestionar datos sobre la vacunación contra el sarampión en Panamá, almacenados en Redis. La aplicación ofrece una interfaz web interactiva para realizar consultas de solo lectura a la base de datos.

## Características
- **Visualización de Datos**: Permite a los usuarios ver todos los registros de vacunación almacenados en Redis.
- **Consulta de Datos por Año**: Los usuarios pueden buscar registros específicos por año a través de la interfaz web.

## Tecnologías Utilizadas
- **Flask**: Un micro framework de Python utilizado para construir aplicaciones web.
- **Redis**: Utilizado como almacenamiento de backend para gestionar los datos de vacunación.
- **HTML/CSS**: Para la interfaz de usuario.

## Estructura del Proyecto
```plaintext
redis_web_app/
│
├── app/
│   ├── __init__.py        # Inicializa la aplicación Flask
│   ├── routes.py          # Define las rutas de la API
│   ├── templates/         # Contiene archivos HTML para la interfaz de usuario
│   ├── static/            # Contiene archivos CSS y JavaScript
│
├── tests/
│   ├── test_app.py        # Pruebas unitarias para la aplicación
│
├── requirements.txt       # Dependencias necesarias para ejecutar la aplicación
├── .gitignore             # Especifica los archivos no rastreados por Git
└── README.md              # Documentación del proyecto

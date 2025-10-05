Estructura Completa del Proyecto AgroControl SAS
Estructura de Directorios
text
northwindMVC/
├── 📁 config/
│   ├── __pycache__/
│   ├── __init__.py
│   └── database.py
├── 📁 controllers/
│   ├── __pycache__/
│   ├── __init__.py
│   ├── base_controller.py
│   ├── cultivos_controller.py
│   ├── fincas_controller.py
│   └── parcelas_controller.py
├── 📁 models/
│   ├── __pycache__/
│   ├── __init__.py
│   ├── base_model.py
│   ├── cultivos.py
│   ├── fincas.py
│   ├── parcelas.py
│   └── 📁 utils/
│       ├── __pycache__/
│       ├── __init__.py
│       ├── exceptions.py
│       ├── helpers.py
│       └── validators.py
├── 📁 views/
│   ├── __pycache__/
│   ├── __init__.py
│   ├── base_view.py
│   ├── cultivos_view.py
│   ├── favicon.ico
│   ├── fincas_view.py
│   ├── main_window.py
│   └── parcelas_view.py
├── 📁 assets/images/
│   ├── employees/
│   │   └── emp_10.jpg
│   └── temp/
│       ├── selected_image_20250917_021...
│       ├── selected_image_20250917_022...
│       ├── selected_image_20250917_022...
│       ├── selected_image_20250917_031...
│       └── selected_image_20250917_032...
├── 📄 main.py
├── 📄 requirements.txt
└── 📄 Documentacion.docx
Módulos Implementados
✅ Cultivos - Gestión de tipos de cultivos

✅ Fincas - Gestión de propiedades agrícolas

✅ Parcelas - Gestión de terrenos de cultivo

Arquitectura del Proyecto
🎯 Patrón MVC (Modelo-Vista-Controlador)

🗃️ Base de datos MySQL con procedimientos almacenados

🖥️ Interfaz Tkinter con temas claro/oscuro

📊 Exportación a Excel y PDF

🛡️ Manejo de errores personalizado

Archivos Principales
main.py - Punto de entrada de la aplicación

database.py - Configuración y conexión a BD

base_model.py - Modelo base con operaciones CRUD

base_controller.py - Controlador base

base_view.py - Vista base con funcionalidades comunes

requirements.txt - Dependencias del proyecto

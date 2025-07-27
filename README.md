# 🧩 CrudUsuarioPHP - Evidencia GA7-220501096-AA5-EV02

Proyecto CRUD en PHP con conexión a MySQL, interfaz HTML y testing completo con Postman.

## 🚀 Funcionalidades

- Registrar usuario desde HTML y Postman.
- Iniciar sesión y cerrar sesión.
- Listar usuarios registrados en panel `dashboard.php`.
- Consultar usuario por ID.
- Actualizar usuario.
- Eliminar usuario.
- Validaciones y respuestas JSON.

## 📁 Estructura de Archivos

/CrudUsuarioPHP/
├── index.html # Formulario HTML para registro e inicio
├── dashboard.php # Panel principal tras iniciar sesión
├── registrar.php # Lógica para registrar usuarios
├── login.php # Lógica para iniciar sesión
├── logout.php # Cierra sesión
├── usuarios.php # Controlador CRUD (GET, POST, PUT, DELETE)
├── conexion.php # Configuración de base de datos
├── repositorio.txt # Enlace al repositorio GitHub
└── pruebas_postman.docx # Evidencia de pruebas en Postman

markdown
Copiar
Editar

## 🧪 Testing con Postman

Se probó toda la API REST usando Postman:
- ✔️ GET todos los usuarios: `/usuarios.php`
- ✔️ GET usuario por ID: `/usuario.php?id=ID`
- ✔️ POST usuario nuevo
- ✔️ PUT para actualizar
- ✔️ DELETE para eliminar

Incluye colección `.json` y captura en `pruebas_postman.docx`.

## 📌 Repositorio GitHub

📎 [https://github.com/jerp1987/CrudUsuarioPHP_Evidencia-GA7-220501096-AA5-EV02](https://github.com/jerp1987/CrudUsuarioPHP_Evidencia-GA7-220501096-AA5-EV02)

## 👨‍💻 Autor

Jhonn Edison Romero Peña  
SENA - Análisis y Desarrollo de Software  
Actividad: GA7-220501096-AA5-EV02

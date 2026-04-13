# Investigacion-Aplicada-2



# Sistema CRUD Asíncrono - ReactPHP
**Materia:** Lenguaje Interpretado en el Cliente  
**Institución:** Universidad Don Bosco (UDB)  
**Estudiante:** José Diego Rivas

Este proyecto es un servidor web asíncrono de alto rendimiento desarrollado con **ReactPHP**. Implementa el paradigma *Event-Driven* para gestionar múltiples solicitudes simultáneas de forma eficiente y no bloqueante.

##  Características
- **Paradigma Event-Driven:** Uso del Event Loop para evitar bloqueos en operaciones de entrada/salida (I/O).
- **CRUD Asíncrono:** Gestión completa de datos (Crear, Leer, Actualizar, Borrar) mediante Fetch API sin recargar la página.
- **Robustez:** Manejo de errores 404 y 500 para una experiencia de usuario profesional.
- **Frontend Moderno:** Interfaz estilizada con Bootstrap 5.

## Requisitos
- PHP 8.1 o superior.
- Composer.
- XAMPP (MySQL).

##  Instalación y Ejecución
1. **Base de Datos:** Importa el archivo SQL incluido en el proyecto (`reactphp_db.sql`) a través de phpMyAdmin.
2. **Dependencias:** Ejecuta el siguiente comando en la raíz:
   ```bash
   composer install

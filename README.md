# API REST para la Administración de Usuarios

Este proyecto consiste en una **API REST** desarrollada en **Node.js** que facilita la administración de usuarios en una base de datos. Está diseñada para ejecutar operaciones esenciales de gestión de datos (CRUD) y puede servir como backend para aplicaciones web o móviles.

## Funcionalidades Clave

- **Operaciones CRUD**: Permite la creación, lectura, actualización y eliminación de usuarios.
- **Autenticación**: Incorpora mecanismos para la verificación y autenticación de usuarios (según la implementación).
- **Integración con Base de Datos**: Se conecta a una base de datos (como MongoDB, MySQL, entre otras) para el almacenamiento y gestión de la información de los usuarios.
- **Manejo de Errores**: Proporciona respuestas claras y estructuradas en caso de errores, facilitando el diagnóstico y solución.
- **Validación de Datos**: Garantiza la integridad de la información mediante la validación rigurosa de los datos de entrada.

# Actualizar registro de las peticiones HTTP
Se ha integrado un middleware en app.js que se encarga de imprimir 
en la consola cada solicitud HTTP que el servidor recibe. Esta funcionalidad 
resulta muy útil para depurar y hacer un seguimiento detallado de las peticiones.
Proyecto Final de Gestión de Tareas

Este proyecto va a implementar una aplicación web en ASP.NET Core MVC con Entity Framework Core que va a gestionar tareas por usuario. Permitira crear, editar, visualizar y listar tareas asignadas, así como llevar un registro de logs de ejecución.

---

Integrantes del grupo

- Karina Picado Aguilar
- Steve Barboza Picado
- Sergio cabezas Martínez

---

Especificación de la arquitectura

El proyecto consta de una arquitectura por capas basada en lo visto en clases:

- APP: Contiene los controladores MVC y vistas Razor (Views/Tarea).
- BLL: Servicios como TareaService, DTOs y reglas de negocio.
- DAL: Contexto de EF Core (ProyectoFinalDbContext) y migraciones.
- ML: Modelos como Tarea, Usuario y LogTarea.

---

Librerías / Paquetes NuGet utilizados

- Microsoft.EntityFrameworkCore
- Microsoft.EntityFrameworkCore.SqlServer
- Microsoft.EntityFrameworkCore.Tools
- Microsoft.AspNetCore.Mvc.Razor.RuntimeCompilation
- AutoMapper
- AutoMapper.Extensions.Microsoft.DependencyInjection
- System.ComponentModel.Annotations

---

Estado del avance

- [x] Creación de base de datos `ProyectoFinalTareaDB`
- [x] Entidades: `Usuario`, `Tarea`, `LogTarea`
- [x] Servicios y DTOs para tareas
- [x] Controlador y vistas para listar y editar tareas
- [ ] Vistas de creación y eliminación (pendiente)
- [ ] Autenticación de usuario (pendiente)

---

Enlace del repositorio de GitHub

https://github.com/Kaguilarp/ProyectoPrograAvanzada.git


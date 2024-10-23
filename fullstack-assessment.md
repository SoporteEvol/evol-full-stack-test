# Prueba Técnica Fullstack - Practicante de Desarrollo

## Objetivo

Desarrollar una aplicación web fullstack simple de gestión de tareas (Todo List) que permita a los usuarios gestionar sus tareas diarias.

## Tiempo Estimado

5-6 días en total

## Requisitos Técnicos

### Frontend (React)

- React ( Vite)
- Axios o fetch para llamadas a la API
- CSS básico (puede usar Bootstrap o Material-UI)

### Backend (elegir uno)

- Spring Boot + Java
- NestJS + TypeScript/JavaScript

### Base de Datos

- H2 (para Spring Boot)
- SQLite (para NestJS)
- Postgres (Recomendado)

## Funcionalidades Requeridas

### 1. Gestión de Tareas

- Crear nueva tarea
- Listar todas las tareas
- Marcar tarea como completada
- Eliminar tarea

### 2. Modelo de Tarea

```json
{
    "id": "number",
    "title": "string",
    "description": "string",
    "completed": "boolean",
    "createdAt": "date"
}
```

### 3. Endpoints API

```
GET    /api/tasks     - Obtener todas las tareas
POST   /api/tasks     - Crear nueva tarea
PUT    /api/tasks/:id - Actualizar tarea (marcar como completada)
DELETE /api/tasks/:id - Eliminar tarea
```

### 4. Interfaz de Usuario

- Formulario simple para crear tareas
- Lista de tareas con:
  - Checkbox para marcar como completada
  - Botón para eliminar
- Diseño responsive básico

## Requerimientos Técnicos Detallados

### Frontend

1. **Componentes Mínimos**

   - Formulario de creación
   - Lista de tareas
   - Componente individual de tarea
2. **Características**

   - Usar hooks básicos (useState, useEffect)
   - Implementar al menos una llamada API
   - Mostrar estados de carga básicos

### Backend

1. **Estructura**

   - Controladores para los endpoints
   - Servicio para lógica de negocio
   - Repositorio para acceso a datos
2. **Características**

   - Validaciones básicas
   - Manejo de errores simple
   - Respuestas HTTP apropiadas

## Puntos Extra (Opcionales)

- Filtrar tareas por estado (completadas/pendientes)
- Ordenar tareas por fecha
- Edición de tareas
- Diseño visual atractivo
- Tests básicos

## Criterios de Evaluación (100 puntos)

### Funcionalidad (40 pts)

- CRUD completo funcionando (20 pts)
- Integración frontend-backend correcta (20 pts)

### Código y Estructura (30 pts)

- Organización del código (15 pts)
- Buenas prácticas básicas (15 pts)

### Frontend (15 pts)

- Interfaz funcional y responsive (10 pts)
- Manejo de estados y efectos (5 pts)

### Backend (15 pts)

- Endpoints funcionando correctamente (10 pts)
- Manejo de datos y errores (5 pts)

## Entregables

1. Repositorio Git con:
   - Código frontend
   - Código backend
   - README con:
     - Instrucciones de instalación
     - Cómo ejecutar el proyecto
     - Tecnologías utilizadas

## Consejos para el Desarrollo

1. Comenzar con el backend y probarlo con Postman/Insomnia
2. Desarrollar el frontend una vez que el backend funcione
3. Integrar ambas partes progresivamente
4. Enfocarse primero en las funcionalidades básicas
5. Agregar características extra solo si hay tiempo

## Notas Importantes

- No es necesario implementar autenticación
- Se permite usar librerías de UI como Bootstrap, Material-UI o Tailwind
- El diseño visual es secundario a la funcionalidad
- Se valorará más el código limpio y funcional que las características extra

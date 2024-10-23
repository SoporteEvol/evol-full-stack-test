## Prueba Backend (Spring Boot / NestJS)

### Objetivo

Desarrollar una API REST simple para gestionar una lista de productos.

### Requerimientos Funcionales

1. **Endpoints de Productos**

   - GET /products - Listar todos los productos
   - GET /products/{id} - Obtener un producto
   - POST /products - Crear producto
   - PUT /products/{id} - Actualizar producto
   - DELETE /products/{id} - Eliminar producto
2. **Características**

   - Validación básica de datos
   - Respuestas HTTP apropiadas
   - Manejo básico de errores

### Modelo de Producto

```json
{
    "id": "string",
    "name": "string",
    "description": "string",
    "price": "number",
    "category": "string"
}
```

### Requisitos Técnicos

#### Opción Spring Boot

- Spring Boot
- Base de datos H2 (en memoria)
- Spring Data JPA
- Controller + Service + Repository

#### Opción NestJS

- NestJS
- Base de datos en memoria o SQLite
- Un módulo con Controller + Service

### Puntos Extra (Opcionales)

- Documentación básica con Swagger
- Tests unitarios básicos
- Filtro de búsqueda por nombre

### Tiempo Estimado

3-4 días

## Criterios de Evaluación

### Backend (50 puntos)

- Implementación de endpoints (20 pts)
- Estructura del código (15 pts)
- Manejo de errores básico (15 pts)

## Entregables

1. Repositorio Git con el código fuente
2. README básico con:
   - Instrucciones de instalación
   - Cómo ejecutar el proyecto
   - Tecnologías utilizadas

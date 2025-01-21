# ForoHub System

ForoHub es una plataforma educativa basada en Spring Boot que permite la creación, gestión y participación en foros. Diseñada con un enfoque en robustez y seguridad, incluye funciones clave para usuarios, temas, cursos y respuestas.

---

## **Índice**
1. [Características]
2. [Arquitectura del Sistema]
3. [Tecnologías Utilizadas]
---

## **Características**

- 🔒 **Gestión de Usuarios**: Autenticación y autorización seguras con JWT.
- 📚 **Gestión de Foros**: Creación, visualización y participación en temas y respuestas.
- 🏫 **Gestión de Cursos**: Asociación de temas con cursos y categorías.
- 📖 **Documentación de la API**: Disponible a través de Swagger.
- 🛡️ **Seguridad Avanzada**: Roles y permisos implementados con Spring Security.

---

## **Arquitectura del Sistema**

El diseño del sistema sigue una arquitectura por capas para maximizar la separación de responsabilidades:

1. **Capa API**: Controladores REST y configuraciones de seguridad.
2. **Capa de Dominio**: Entidades, repositorios y DTOs.
3. **Capa de Infraestructura**: Configuración de base de datos, manejo de errores y documentación de la API.

---

## **Tecnologías Utilizadas**

| Categoría          | Tecnología                     |
|--------------------|--------------------------------|
| **Lenguaje**       | Java 17                        |
| **Framework**      | Spring Boot                   |
| **Seguridad**      | Spring Security, JWT          |
| **Acceso a Datos** | Spring Data JPA, Hibernate    |
| **Base de Datos**  | MySQL                         |
| **Documentación**  | SpringDoc OpenAPI (Swagger)   |

---
### **Prerrequisitos**
- 📦 JDK 17
- 🛠️ Maven 3.8+
- 🗄️ MySQL 8.0+


### **Endpoints Principales**

| Método | Endpoint                  | Descripción                            |
|--------|---------------------------|----------------------------------------|
| POST   | `/auth/login`             | Autenticar un usuario.                 |
| GET    | `/users`                  | Obtener lista de usuarios.             |
| GET    | `/topics`                 | Listar todos los temas.                |
| POST   | `/topics`                 | Crear un nuevo tema.                   |
| GET    | `/courses`                | Listar todos los cursos.               |
| POST   | `/responses`              | Publicar una respuesta en un tema.     |

---



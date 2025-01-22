## ForoHub System: Guía Técnica

ForoHub es una plataforma educativa basada en Spring Boot que permite la creación, gestión y participación en foros. Este proyecto implementa un sistema robusto y seguro para usuarios, temas, cursos y respuestas.

## Características Principales

- **Gestión de Usuarios**: Autenticación y autorización con JWT.

- **Gestión de Foros**: Creación y visualización de temas y respuestas.

- **Gestión de Cursos**: Asociación de cursos con temas y categorías.

- **Documentación de la API**: Generada con Swagger.

- **Seguridad**: Implementación de roles y permisos con Spring Security.

## Arquitectura del Sistema

El proyecto está diseñado con una arquitectura por capas:

- **Capa API**: Contiene los controladores REST y configuraciones de seguridad.

- **Capa de Dominio**: Define las entidades, repositorios y DTOs.

- **Capa de Infraestructura**: Incluye configuración de base de datos, manejo de errores y documentación de API.

## Tecnologías Utilizadas

- **Lenguaje**: Java 17

- **Framework Principal**: Spring Boot

- **Seguridad**: Spring Security, JWT

- **Acceso a Datos**: Spring Data JPA, Hibernate

- **Base de Datos**: MySQL

- **Documentación**: SpringDoc OpenAPI (Swagger)

## Configuración e Instalación

## Prerrequisitos

- JDK 21

- Maven 3.8+

- MySQL 8.0+

## Pasos para la Instalación

- Clonar el repositorio de GitHub.

- Configurar la base de datos: crear una base de datos en MySQL y actualizar las credenciales en el archivo `application.properties`.

- Compilar y ejecutar la aplicación utilizando Maven.

- Acceder a la documentación de la API en `http://localhost:8080/swagger-ui.html`.

## Endpoints Principales

| Método | Endpoint      | Descripción                |
| ------ | ------------- | -------------------------- |
| POST   | `/auth/login` | Autenticar un usuario.     |
| GET    | `/users`      | Obtener lista de usuarios. |
| GET    | `/topics`     | Listar todos los temas.    |
| POST   | `/topics`     | Crear un nuevo tema.       |
| GET    | `/courses`    | Listar todos los cursos.   |
| POST   | `/responses`  | Publicar una respuesta.    |



Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
# Alura_Challenge-Foro-Hub

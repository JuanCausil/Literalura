# 📚 Proyecto LiterAlura

Este proyecto fue desarrollado en Java utilizando **Spring Boot**, como parte del Challenge Back-End de **Alura + Oracle Next Education (ONE)**. Permite consultar libros desde la API pública de **Gutendex**, guardar información relevante en una base de datos y visualizarla desde consola o navegador.

---

## 🚀 Funcionalidades

- Conexión a la API [Gutendex](https://gutendex.com/)
- Consulta de libros por autor
- Registro de libros en base de datos PostgreSQL
- Menú interactivo por consola
- Visualización de libros almacenados
- Filtro por idioma y otros criterios
- Integración con JPA/Hibernate

---

## 🛠️ Tecnologías utilizadas

- Java 17
- Spring Boot 3.5.0
- Spring Data JPA
- PostgreSQL
- Maven
- API REST (Gutendex)

---

## 📂 Estructura del proyecto
literalura/
├── src/
│ ├── main/
│ │ ├── java/com/literalura/
│ │ │ ├── model/
│ │ │ ├── repository/
│ │ │ ├── service/
│ │ │ ├── Principal.java
│ │ └── resources/
│ │ ├── application.properties
├── pom.xml


---

## ⚙️ Requisitos

- JDK 17
- Maven 3.9.x o superior
- PostgreSQL instalado y en funcionamiento

---

## 🔧 Configuración de la base de datos

Asegúrate de que tu archivo `application.properties` esté así:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/literalura
spring.datasource.username=postgres
spring.datasource.password=PostgreSQL2024
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true


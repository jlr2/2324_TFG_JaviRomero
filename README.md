# Club Náutico App

Esta es una aplicación de ejemplo para gestionar un club náutico utilizando Spring Boot y una base de datos MySQL.

## Requisitos

Antes de ejecutar la aplicación, asegúrate de tener instalado XAMPP o tener una base de datos MySQL instalada en tu sistema. Además, necesitas haber creado una base de datos llamada `clubnautico` en tu servidor MySQL.

## Configuración de la base de datos

La aplicación está configurada para usar la siguiente configuración de base de datos:

```properties
spring.application.name=clubnautico
spring.datasource.url=jdbc:mysql://localhost:3306/clubnautico?serverTimezone=UTC
spring.datasource.username=root
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

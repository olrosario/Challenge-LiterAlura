# CHALENGE LITERALURA

## DESCRIPCION 
LiterAlura es una aplicación de catálogo de libros construida con Spring Boot que interactúa con la API de Gutendex para obtener y almacenar información sobre libros en una base de datos PostgreSQL. La aplicación permite buscar libros, guardarlos en la base de datos y visualizar los libros más descargados.

![img_1.png](../../../target/img_1.png)

## ¿Qué puedes hacer con Literalura?

- Agregar Libro por Nombre
- Libros buscados
- Buscar libro por Nombre
- Buscar todos los Autores de libros buscados
- Buscar Autores por año
- Buscar Libros por Idioma
- Top 5 Libros más Descargados
- Buscar Autor por Nombre
 
## Requisitos
- Java JDK 17 o superior
- Maven 4 o superior
- Spring Boot 3.2.3
- PostgreSQL 16 o superior
- IntelliJ IDEA (opcional)

## ¿Cómo empezar?
## Instalación
## Clonar el Repositorio:
- git clone https://github.com/olrosario/Challenge-LiterAlura.git

## Configurar la Base de Datos
- Instalar PostgreSQL y crear una base de datos para el proyecto.
- Configurar el archivo application.properties con los detalles de la base de datos:

- ![img.png](../../../target/img.png)

## Estructura del Proyecto
- src/main/java/com/example/literalura:
- - Código fuente principal
- - entity: Clases de entidad JPA
- - repository: Interfaces de repositorio de Spring Data JPA
- - service: Clases de servicio
- - controller: Controladores REST
- - config: Configuración de Spring
- src/main/resources: Recursos de la aplicación
- - application.properties: Configuración de la base de datos y otras propiedades
- - pom.xml: Contiene las dependencias del proyecto

## Funciones del desarrollo

## Menú:

![img_2.png](../../../target/img_2.png)

Información almacenada en la Base de Datos de PostgresSQL ya consumida de la API-Gutendex:

![img_3.png](../../../target/img_3.png)
![img_4.png](../../../target/img_4.png)
![img_5.png](../../../target/img_5.png)
![img_6.png](../../../target/img_6.png)

## Top 5 libros más descargados 
![img_7.png](../../../target/img_7.png)




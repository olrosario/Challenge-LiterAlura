Este es mi Challenge de LiterAlura del Curso One Alura Latam 

# CHALENGE LITERALURA

## DESCRIPCION
LiterAlura es una aplicación de catálogo de libros construida con Spring Boot que interactúa con la API de Gutendex para obtener y almacenar información sobre libros en una base de datos PostgreSQL. La aplicación permite buscar libros, guardarlos en la base de datos y visualizar los libros más descargados.
![image](https://github.com/olrosario/Challenge-LiterAlura/assets/157546975/8c57a7aa-1b54-4380-9346-e61bdd459e6c)


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

# Instalación
## ¿Cómo empezar?
## Instalación
## Clonar el Repositorio:
- git clone https://github.com/olrosario/Challenge-LiterAlura.git

## Configurar la Base de Datos
- Instalar PostgreSQL y crear una base de datos para el proyecto.
- Configurar el archivo application.properties con los detalles de la base de datos:
![image](https://github.com/olrosario/Challenge-LiterAlura/assets/157546975/4e19807c-174b-44c5-9b36-356148462b5d)

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
![image](https://github.com/olrosario/Challenge-LiterAlura/assets/157546975/0b120708-4d7d-46c5-9101-27a71fb2aafe)

Información almacenada en la Base de Datos de PostgresSQL ya consumida de la API-Gutendex:
![image](https://github.com/olrosario/Challenge-LiterAlura/assets/157546975/d22823ee-c5a6-42ae-9f7c-a9650ab7f351)

![image](https://github.com/olrosario/Challenge-LiterAlura/assets/157546975/a9ccda51-6266-4a4b-bc4e-afa1e7b03f52)

![image](https://github.com/olrosario/Challenge-LiterAlura/assets/157546975/be14424e-bdcf-43c9-88e3-d690eb99899c)

![image](https://github.com/olrosario/Challenge-LiterAlura/assets/157546975/94ed59f5-ce8c-416b-90ad-1e0ae958213b)


## Top 5 libros más descargados 
![image](https://github.com/olrosario/Challenge-LiterAlura/assets/157546975/092d7fc6-1264-4168-92c2-c011d297b369)

## Créditos
Este Proyecto fue elaborado por Olga Rosario

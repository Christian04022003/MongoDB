Modelos de Datos (Movie.java, Review.java):
Se definieron las clases Movie y Review como modelos de datos utilizando anotaciones de Lombok para generar getters, setters y constructores de forma automática.
La clase Movie contiene atributos como imdbId, title, releaseDate, trailerLink, poster, backdrops y genres, que representan información sobre una película.
La clase Review contiene atributos como body, created, y updated, que representan una reseña de una película.
Repositorios (MovieRepository.java, ReviewRepository.java):
Se crearon interfaces de repositorio utilizando Spring Data MongoDB para interactuar con la base de datos MongoDB.
Estas interfaces proporcionan métodos para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en las colecciones de películas y reseñas.
Servicios (MovieService.java, ReviewService.java):
Se implementaron clases de servicio que contienen la lógica de negocio para manipular datos relacionados con películas y reseñas.
Estas clases utilizan los repositorios correspondientes para interactuar con la base de datos y realizar operaciones como buscar todas las películas, buscar películas por su IMDb ID, crear nuevas reseñas, etc.
Controladores REST (MovieController.java, ReviewController.java):
Se definieron controladores REST utilizando anotaciones de Spring para manejar las solicitudes HTTP relacionadas con películas y reseñas.
Estos controladores exponen puntos finales RESTful que permiten a los clientes realizar operaciones como obtener todas las películas, obtener una película por su IMDb ID, y crear nuevas reseñas.

# Aplicación de Gestión de Películas con Java Spring Boot y MongoDB

Este proyecto es una aplicación de gestión de películas desarrollada utilizando Java Spring Boot para el backend y MongoDB como base de datos no convencional.

## Descripción

Esta aplicación permite a los usuarios buscar y explorar información sobre películas, ver detalles como la sinopsis, fecha de lanzamiento, géneros, trailers y pósters, así como dejar reseñas y calificaciones.

## Funcionalidades

- Búsqueda y exploración de películas por título, género, o fecha de lanzamiento.
- Visualización de detalles de películas, incluyendo sinopsis, fecha de lanzamiento, géneros, trailers y pósters.
- Creación y visualización de reseñas y calificaciones para películas.
- API RESTful para interactuar con los datos de películas y reseñas.

## Herramientas Utilizadas

- Java Spring Boot: Framework de desarrollo de aplicaciones web en Java.
- MongoDB: Base de datos no relacional utilizada para almacenar información sobre películas y reseñas.
- Lombok: Biblioteca de Java que simplifica la escritura de código eliminando la necesidad de escribir getters, setters y constructores manualmente.

## Instalación y Ejecución

1. Clona el repositorio:

```bash
git clone https://github.com/Christian04022003/MongoDB.git

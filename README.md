# Doggy API RESTful

## Introducción

Doggy API es una API RESTful creada con el objetivo de brindar información sobre las diferentes razas de perros que hay en la actualidad.
Las fuentes de información utilizadas para este proyecto son:
*  [Purina](https://purina.es/perros/razas-de-perro/tipos-de-razas-de-perro)
*  [FCI - Federation Cynologique Internationale](http://www.fci.be/es/)

La API fue desarrollada con node.JS y MongoDB, y se encuentra alojada en Heroku

## Uso de la API

Para realizar peticiones a la API se debe acceder al siguiente enlace: [Doggy-API](https://doggy-api.herokuapp.com/api/dogs)

## Estructura de la API

Cada objeto dentro de la API cuenta con la siguiente estructura:
  1. Nombre
  2. Descripción
  3. Imagen (*no disponible por el momento*)
  4. Altura
      1. Mínima
      2. Máxima
  5. Peso
      1. Mínimo
      2. Máximo
  6. Pelaje
      1. Tipo
      2. Color
  7. Uso
  8. Origen
  9. Personalidad
  10. Salud
  11. Ejercicio
  12. Nutrición
  13. Aseo

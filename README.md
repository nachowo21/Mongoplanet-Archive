# MongoPlanet Archive
## Introduccion

MongoPlanet Archive es un proyecto que utiliza los datos del [Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu) para crear una base de datos no relacional utilizando MongoDB. Esto se debe a que los datos descargados de la plataforma oficial son extensos y complejos de interpretar en su formato original. Por lo tanto, transformamos esta información en un formato más accesible y estructurado, empleando bases de datos del tipo documento para facilitar su comprensión y análisis.

## Objetivo

Simplificar la lectura de los datos del Exoplanet Archive, facilitar su exploración y análisis a través de MongoDB, y generar visualizaciones como histogramas para interpretar la información proporcionada por este catálogo. hacer que se agrupe por grupo cada sistema estelares 

## Diagrama

![Diagrama ER de base de datos (pata de gallo)(6)](https://github.com/user-attachments/assets/d3299766-f015-4d05-8151-bfda7a042c2d)



## Características

- Transformación de datos: convertimos los datos del catalogo en un formato que puede ser almacenado y gestionado con Mongodb
- Automatización: Usamos python para realizar el script de poblacion de datos con ayuda de pymongo
- Visualización de datos: Hicimos histogramas para los metodos de descubrimiento, para así entender la información que nos entrega esta base de datos

## Requisitos

- Python 3.7 o superior
- MongoDB (local o en un servidor)

- las siguientes bibliotecas de python:
  - pymongo versión 2.0
  - pandas versión 2.2.3
  - matplotlib versión 3.9.2
  - numpy versión 1.26.4
  - astropy versión 6.1.3


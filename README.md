## Proyecto Individual - Machine Learning 


**Objetivo:** 🚀

 Utilizando una base de datos sobre propiedades publicadas en estados unidos, realicé 2 modelos de predicción para categorizarlos. 
 
 **Descripción del problema:**

Hemos sido contactados para el área de Machine Learning de una importante empresa inversora dentro del rubro de la inmobiliaria en Estados Unidos. ​El Team Lider le propone dos predicciones posibles, de las cuales puede elegir cuál realizar (o ambas si así lo quiere):​

1. Implementar un modelo de clasificación con aprendizaje supervisado que permita clasificar el precio de las propiedades en venta, utilizando los datos que se han puesto a su disposición. ​Para esto debe crear la columna category_price, en la cual se consideran las siguientes categorías:
    * 'low': Para precios entre 0 y 999 dólares (debe tomar valor 1 en el archivo con las predicciones).
    * 'high': Para precios desde 1000 dólares en adelante (debe tomar valor 0 en el archivo con las predicciones). ​Considerando esta categorización, el objetivo es predecir si una propiedad pertenece a la categoría de precios bajos (low).​
2. Implementar un modelo de clasificación con aprendizaje no supervisado, utilizando clustering que agrupe las propiedades por segun las siguientes categorias:
    * 'low': Para precios entre 0 y 999 dólares (debe tomar valor 1 en el archivo con las predicciones).
    * 'medium': Para precios entre 1000 y 1999 dólares (debe tomar valor 0 en el archivo con las predicciones).
    * 'high': Para precios desde 2000 dólares en adelante (debe tomar valor 0 en el archivo con las predicciones).​

Para ello, solo usaran el dataset de test provisto, eliminando previamente las caracteristicas que presenten nulos.​

**Modelo Supervisado:** 

Datasets RAW:
* [train.parquet](https://drive.google.com/file/d/1PEniLDqZVbbO5bafFyHDWBagLSYPEaL_/view?usp=share_link) <br>
* [test.parquet](https://drive.google.com/file/d/1k_Phe1qPdf8nUIRBv35Blpv9GTF-G2lM/view?usp=share_link) <br>
* De igual manera se encuentran alojados en la carpeta Data.


Utilicé las base de datos proporcionadas, y un modelo de aprendizaje de Arbol de Clasificación. 

**Modelo NO-Supervisado:**

Datasets RAW:
* [test.parquet](https://drive.google.com/file/d/1FhzxwBPEdCVAYQHuuWkg4hggpC9l1xn1/view?usp=share_link)

:white_medium_small_square: Utilicé las base de datos proporcionadas, y un modelo de aprendizaje K-Means. 

**Sobre los Notebooks:**  

 Ambos notebooks contienen el paso a paso de la creación del pipeline, el analisis exploratorio de los datos y el modelo en cuestión. 


🦾 con ❤️ por [Camilo Ardila🤖](https://github.com/kmilo140) 😊  


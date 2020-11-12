# Properati price inference

En el presente proyecto exploramos un dataset que contiene una colección de propiedades inmobiliarias del sitio web [Properati](https://www.properati.com.ar/) para el año 2017, más aún, implementamos un regresor para realizar inferencias sobre el precio de las propiedades utilizando datos cerrados y texto que contienen las publicaciones en el dataset.

## Estructura del repositorio

El scaffolding se encuentra dispuesto de la siguiente manera:

* [0_Exploratory_Data_Analysis.ipynb](0_Exploratory_Data_Analysis.ipynb): muestra el analisis y exploracion de los datos.
* [1_Regresion_Properati_Final.ipynb](1_Regresion_Properati_Final.ipynb): implementa un regresor realizando tuneo de hiperparámetros.
* [properati.zip](properati.zip): tiene de forma comprimida el archivo ```properati.csv```, el cual es necesario para ejecutar las notebooks.
* [Exploracion](Exploracion): contiene notebooks explorando y graficando desde distintos puntos el dataset, estas notebooks fueron unidas utilizando nbmerge para crear la primer notebook que contiene toda la exploracion.


## Resultados de la exploración de datos

### Distribución 1
![](https://github.com/cnexans/properati-price-inference/blob/master/Imagenes/distribuci%C3%B3n.png)

### Distribución ciudades
![](https://github.com/cnexans/properati-price-inference/blob/master/Imagenes/distribucionciudades.png)

### Tasa de conversión
![](https://github.com/cnexans/properati-price-inference/blob/master/Imagenes/conversion.png)

### Outliers superficie
![](https://github.com/cnexans/properati-price-inference/blob/master/Imagenes/outlierssurface.png)

### Precio por tipo de propiedad
![](https://github.com/cnexans/properati-price-inference/blob/master/Imagenes/precioportipo.png)

### Superficie cubierta por tipo
![](https://github.com/cnexans/properati-price-inference/blob/master/Imagenes/surface_covered_propiedad.png)

### Wordcloud de comentarios de propietario
![](https://github.com/cnexans/properati-price-inference/blob/master/Imagenes/wordcloud.png)

## Algunas consideraciones sobre el tratamiento de datos

El dataset de Properati año 2017 al que accedimos para realizar este proyecto se encontraba con muchos errores. Algunas estrategias para subvertirlos fueron:

*[Imputación]
*[Limpieza de nulos]
*[Se acudió al registro de conversión para poder realizar la misma desde monedas regionales a USD teniendo en cuenta su fecha de publicación]
*[Algunas propiedades fueron relocalizadas teniendo en cuenta los límites comunales de la Capital Federal]


## Equipo

* [Guido Mitolo](https://github.com/guidomitolo)
* [Thomas Artopoulos](https://github.com/thomasartopoulos)
* [Jonatan Smith](https://github.com/John31991)
* [David G. Nexans](https://github.com/cnexans)

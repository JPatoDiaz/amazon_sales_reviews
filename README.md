# Análisis de los reviews de Amazon Sales

## Contexto

Amazon es una empresa de tecnología estadounidense con operación multinacional, cuyos intereses comerciales incluyen el comercio electrónico, para el que compran y almacenan el inventario, y se encargan de todo el proceso, desde fijar los precios hasta el envío, el servicio al cliente y las devoluciones.

A través del procesamiento de lenguaje natural y otras técnicas de análisis - cohortes y validación de hipótesis- se buscó  comprender dicen los reviews de los productos más vendidos en Amazon.


## ¿Cuál fue el objetivo? 

Analizar a través del procesamiento de lenguaje natural y otras técnicas de análisis - cohortes y validación de hipótesis que nos dicen los reviews de los productos más vendidos en Amazon. 

Adicional se buscará validar las siguientes hipótesis: 
-   Existe relación entre precio y calificación
-   Cuanto mayor sea el descuento mejor será la puntuación
-   Cuanto mayor sea el número de personas que evaluaron el producto, mejor será la calificación

## ¿Qué insumos/herramientas usamos para el análisis?  

### Insumos

- Set de datos público con la información de más de 1700 reseñas de productos comprados a través de Amazon

### Herramientas

- GoogleColab
- GoogleCloud
- Tableau

### Lenguajes

- SQL 
- Python 


## ¿Cuál fue el proceso de trabajo?  

El desarrollo del proyecto se llevo a través de las siguientes fases

-  Procesar y preparar los datos con consultas en SQL identificando valores nulos, duplicados y fuera del alcance del análisis
- Categorización de sentimiento de los reviews en Phyton a través de la librería TextBlob que usa programación de lenguaje natural, para clasificar los reviews en tres categorías: Positivas, negativas y neutras
- Análisis de cohortes de los descuentos dados en la compra de cada uno de los productos usando Phyton
- Validación de hipótesis  en Phyton a través del calculo de correlaciones entre variables 
- Construcción de un dashboard usando Tableau como herramienta de visualización
- Presentación a stakeholders de los resultados y las recomendaciones 


## Archivos adicionales

**[https://console.cloud.google.com/welcome?project=datalab-414617](https://console.cloud.google.com/welcome?project=datalab-414617)**


## Imágenes de resultados

![enter image description here](https://github.com/JPatoDiaz/amazon_sales_reviews/blob/main/imagenes/DashboardAmazonSales.png)

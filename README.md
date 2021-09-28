# Proyecto_Clasificacion_Imagenes
Este proyecto se ha realizado como ejercicio de de proponer un modelo clasificador de imagenes de flores, desde distintos puntos aproximación:
* **Clasterización**  -  Preprocesamiento de imagenes, extracción de features, reducción de dimensionalidad PCA, TSNE. Clasterización con K-Means y DBSCAN.
* **Semi-Supervisado**  -  Utilización LabelSpreading, etiquetando parte del dataset de entrada y las otras etiquetas claularlas de las etiquetas que predice el clasificador.
* **Red Neuronal Convolucional-CNN** - Aproximación desde el Deep Learning, con una red convolucional que están optimizadas para estas cuestiones con imagenes.

## Contenido y Estrutura del proyecto
El proyeto se divide en 2 notebooks y 2 carpetas **technical_test_images_cnn** e **img**:

* **Clasterizacion_&_Semi_Supervisado.iypnb**  -  En este notebook es donde se encuentra el modelo de clasterización y el semi-supervisado.
* **Red CNN.iypnb**  -  En este notebook es donde están el modelo de la CNN.

### Carpeta "technical_test_images_cnn"
En esta carpeta residen los ficheros de las imagenes para la parte de entrnamiento, validación y test:
### Carpeta "img"
Imagenes utilizadas en los notebooks.



## Principales librerias utilizadas.

* **pandas**
* **numpy**
* **matplotlib**
* **tensorflow 2.6**
* **imageio**
* **skimage**
* **shapely**
* **glob**
* **sklearn**
* **scipy**

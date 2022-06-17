# DP4-X-RayClassification

## Grupo 4
    · Marta Castillo García
    · Enrique Badenas Cazorla

Data Project #4 - Clasificación de imágenes de radiografías según la anatomía radiografiada

Desafío disponible en Kaggle: https://www.kaggle.com/competitions/edemdataproject4 

Entregable: dos ficheros Notebook de Google Colab

#1: DP4_G4 load_transform_describe para descargar los datos desde Kaggle, cargarlos, descomprimir, extraer las imágenes del formato DICOM y colocarlas en carpetas según la clase a la que pertenece cada una de ellas en el grupo TRAIN según el fichero que contiene sus etiquetas train.csv.

#2: Models

Etapas realizadas
- Descarga de los datos desde Kaggle
- Extraer las imágenes de los formatos DICOM para transformarlas a formatos menos pesados como jpg o png
- Con ayuda del fichero train.csv hacer y clasificar las imágenes según su clase en una carpeta con el nombre de clase
- Aplicar transformaciones básicas a las imágenes para aumentar la cantidad de imágenes con las que entrenar
- Entrenar modelos (diferentes redes neuronales de fastai)
- Según el performance de los modelos realizar modificaciones sobre el número de epochs y resolución
- Creación del fichero submission con los datos de validación



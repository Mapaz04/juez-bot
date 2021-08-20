# Juez Bot

_Este proyecto tiene el objetivo de predecir las decisiones de la Comisión de Protección al Consumidor de INDECOPI_

## Estructura del repositorio

Este repositorio está dividido en tres secciones principales y una de exploración:

1. Reading-Resolutions: 
    - Para predecir las decisiones debemos recurrir a las resoluciones disponibles de INDECOPI las cuales se encuentran organizadas [aquí](https://drive.google.com/drive/folders/1IqCEtThpjyWSVTAYmQgt1MHVYPKG1LEk?usp=sharing).
    - Luego debemos realizar un primer procesamiento del documento donde convertimos de pdf a txt
    - Procedemos con todo el procedimiento de text mining de estas resoluciones, todo ello se encuentra en el archivo _procesamiento de de documentos_.
2. Preprocesing-vectorization:
    - Lo siguiente es, a partir de lo anterior, estructura la data en tablas. [Aquí](https://drive.google.com/drive/folders/1VRlICMyEpSUGHjdXvfi7sLpSfz3wNWnI?usp=sharing) vemos el resultado final de todas las resoluciones procesadas y organizadas por distintos años
    - Estas tabalas servirán de input para vectorizar bajo distintos métodos:
        * Binario
        * TF-IDF
        * Embeddings
3. Modeling:
    - En esta sección procedemos a realizar los modelos de aprendizaje supervisado que nos permitirán predecir:
        * MLP
        * SVM
        * Random Forest
Finalmente se tiene una sección de bonus que nos da un alcance de exploración de los datos: 4. Exploracion-data



### Pre-requisitos

_Todo el proyecto se encuentra hecho en Python 3.8.0 con el uso de las siguientes librerías:_

* pdfminer
* xlwt


## Autores

* **Diego Alvarado** El hacker
* **Maria Paz Herrera** La gfa
* **Diego Mayandia** Barbitas


Programado con ❤️

#laFe
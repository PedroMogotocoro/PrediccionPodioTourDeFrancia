# Predicción del podio en el Tour de Francia: Un enfoque de clasificación y ordenamiento

Este repositorio contiene el desarrollo computacional de una investigación orientada a identificar y analizar las características y variables asociadas con la posibilidad de que un corredor, habiendo finalizado entre los diez primeros puestos (*Top 10*) de la clasificación general del Tour de Francia, ocupe una posición en el podio final.

Para abordar este problema, se desarrollaron diferentes etapas metodológicas: recopilación y organización de datos, construcción e integración de bases de datos, selección de variables, implementación de algoritmos de clasificación y ordenamiento, análisis de la importancia de las variables y evaluación de los resultados obtenidos.

El propósito de este repositorio es servir como soporte computacional y complemento de la investigación desarrollada en el marco de una tesis de pregrado en Matemática Aplicada. Se busca proporcionar acceso a los procedimientos implementados, los datos utilizados y los resultados obtenidos, de manera que el desarrollo metodológico pueda ser consultado y examinado.

En su contenido se encuentran los cuadernos de Jupyter utilizados durante la investigación, los conjuntos de datos empleados en las distintas etapas del procesamiento, las implementaciones de los modelos y los archivos complementarios necesarios para comprender el procedimiento desarrollado.

Este material tiene como finalidad documentar el proceso de investigación y facilitar la consulta de los métodos computacionales que respaldan los resultados presentados en el documento de tesis.



## Estructura del repositorio

| Archivo o carpeta | Descripción |
|---|---|
| `Notebooks/` | Contiene los cuadernos de Jupyter utilizados para el desarrollo computacional de la investigación. |
| `Revision Data Top 10.ipynb` | Contiene los procedimientos de revisión, organización y preparación de los datos de los corredores que finalizaron en el Top 10 del Tour de Francia. |
| `TDGMej.ipynb` | Contiene el desarrollo de los modelos de clasificación y ordenamiento, la selección de variables, el ajuste de modelos y la evaluación de resultados. |
| `Datos/` | Contiene los conjuntos de datos recopilados y procesados durante la investigación. |
| `DataDesTop10.csv` | Contiene las variables de los ciclistas que finalizaron en el Top 10 de las ediciones del Tour de Francia entre 2006 y 2024. |
| `PSC_GC.csv` | Contiene la información correspondiente a la variable PCS GC Ranking, obtenida del portal ProCyclingStats. |
| `cyclingdata.csv` | Contiene información histórica de carreras de ciclismo desde sus inicios hasta 2024, incluido el Tour de Francia. Se utiliza para extraer información de las carreras correspondientes al periodo de investigación. |
| `tour_dataset_final.csv` | Contiene las variables de los corredores y de las ediciones del Tour de Francia. Constituye el conjunto de datos base utilizado en la investigación. |

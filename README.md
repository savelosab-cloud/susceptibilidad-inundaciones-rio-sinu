# susceptibilidad-inundaciones-rio-sinu


#Evaluación Comparativa de Modelos Digitales de Elevación para la Estimación de Susceptibilidad a Inundaciones mediante Modelos Random Forest en la Cuenca Baja del Río Sinú


#Descripción

Este repositorio contiene los datos, scripts, notebooks y resultados asociados al desarrollo de una Evaluación Comparativa de Modelos Digitales de Elevación para la Estimación de Susceptibilidad a Inundaciones mediante Modelos Random Forest en la Cuenca Baja del Río Sinú, departamento de Córdoba, Colombia.

El estudio evalúa la influencia de diferentes modelos digitales de elevación (MDE) sobre la generación de variables topográficas e hidrológicas y su capacidad para representar las condiciones espaciales asociadas a la ocurrencia de inundaciones.

Se comparan tres fuentes de elevación: Copernicus GLO-30, FABDEM V1-2 y ANADEM. A partir de estos modelos se derivan conjuntos de variables predictoras que posteriormente se utilizan en experimentos de clasificación mediante Random Forest.

#Objetivo

Evaluar cómo las diferencias entre modelos digitales de elevación se reflejan en las variables topográficas e hidrológicas derivadas y en el desempeño de modelos de clasificación orientados a estimar la susceptibilidad espacial a inundaciones.

#Datos utilizados

Copernicus GLO-30: modelo digital de superficie con resolución aproximada de 30 m.
FABDEM V1-2: modelo de elevación con correcciones orientadas a reducir los efectos de edificios y vegetación.
ANADEM: modelo digital de terreno diseñado para Suramerica
Sentinel-1: imágenes de radar utilizadas para la identificación de áreas inundadas y la construcción del inventario.
Red de Control Vertical: información altimétrica de referencia para la evaluación de los modelos de elevación.

#Metodología

El flujo de trabajo comprende las siguientes etapas:

1.Configuración del entorno de procesamiento y obtención de los modelos digitales de elevación.
2.Armonización espacial de los modelos mediante un sistema de referencia y una malla común.
3.Comparación altimétrica de los MDE con puntos de control vertical.
4. DErivación de variables topográficas e hidrológicas.
5.Construcción del inventario de inundaciones a partir de información Sentinel-1.
6.Preparación de muestras espaciales comunes para los experimentos.
7.Entrenamiento, evaluación y comparación de modelos Random Forest.

#Experimentos

Se desarrollan tres experimentos:

Experimento A: predictores derivados de Copernicus GLO-30.
Experimento B: predictores derivados de FABDEM V1-2.
Experimento C: predictores derivados de ANADEM.

Los experimentos se plantean bajo un esquema metodológico común para facilitar la comparación entre las fuentes de elevación.

#Herramientas

Google Earth Engine
Google Colab
Python
ArcGIS Pro

Estructura del repositorio

El repositorio organiza los notebooks de procesamiento, scripts de Google Earth Engine, datos de entrada, productos intermedios, resultados y documentación metodológica.

Autoría

Autor: Sebastian Velosa Bohorquez
Institución: Universidad Nacional de Colombia
Programa: Maestría en Geomática


Estado del proyecto

[En desarrollo]


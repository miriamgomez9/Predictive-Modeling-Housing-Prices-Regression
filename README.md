# Predictive-Modeling-Housing-Prices-Regression

Flujo avanzado de mineria de datos y modelizacion predictiva sobre el mercado inmobiliario utilizando el dataset House Prices de Kaggle. Implementa preprocesamiento masivo, reduccion de dimensionalidad y comparacion de modelos de regresion complejos.

## Descripcion del Proyecto
Este trabajo aborda el problema socioeconomico de la prediccion del precio de venta de propiedades inmobiliarias. Utilizando un enfoque metodologico riguroso, se analiza la influencia de multiples factores estructurales, materiales y de entorno sobre el valor de la vivienda. El fin principal es optimizar la precision predictiva de los modelos supervisados mientras se evalua la capacidad de interpretacion de las variables en escenarios reales de tasacion.

## Conjunto de Datos
Los datos corresponden al problema House Prices - Advanced Regression Techniques disponible en Kaggle. El dataset cuenta con mas de 1400 observaciones y mas de 70 variables cuantitativas y cualitativas que detallan caracteristicas como la calidad de los materiales, metros cuadrados habiles, ano de construccion, remodelaciones y localizacion.

## Metodologia y Pipeline de Desarrollo

### 1. Preprocesamiento e Ingenieria de Variables
* Imputacion de datos nulos fundamentada en la naturaleza de cada variable para evitar sesgos en el modelado.
* Transformacion logaritmica de la variable objetivo Precio de Venta para mitigar la asimetria y estabilizar la varianza.
* Codificacion y tratamiento homogeneo de variables cualitativas nominales y ordinales.

### 2. Analisis No Supervisado y Reduccion de la Dimension
* Estandarizacion de los datos para evitar distorsiones por diferencias de escala.
* Analisis de Componentes Principales para sintetizar la informacion de las variables originales en un conjunto reducido de componentes latentes.
* Algoritmos de clustering para segmentar y perfilar tipologias de viviendas basandose en sus caracteristicas intrinsecas.

### 3. Modelado Predictivo
Implementacion y optimizacion hiperparametrica de modelos bajo dos enfoques contrapuestos:
* Modelos interpretables: Regresiones lineales con regularizacion Ridge y Lasso para controlar el sobreajuste y seleccionar variables clave.
* Modelos de alta capacidad predictiva: Arboles de decision avanzados, ensamblados y arquitecturas de Redes Neuronales Artificiales optimizadas para minimizar el error cuadratico medio.

## Tecnologias Utilizadas
* Python como lenguaje de programacion principal.
* Pandas y NumPy para la gestion de estructuras de datos y calculo numerico.
* Matplotlib y Seaborn para la visualizacion estadistica y diagnoticos de los modelos.
* Scikit-Learn para el preprocesamiento, escalado, reduccion de dimensiones y algoritmos de machine learning.

## Informacion Academica
* Universidad Carlos III de Madrid, 4 Curso
* Asignatura: Metodos estadisticos en mineria de datos
* Autor: Miriam Gomez Arias

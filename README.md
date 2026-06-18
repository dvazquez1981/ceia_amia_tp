# Trabajo Práctico 1 – LDA, QDA y Optimización Matemática de Modelos

## Introducción

Este trabajo práctico tiene como objetivo estudiar, implementar y optimizar algoritmos de clasificación supervisada basados en modelos probabilísticos, específicamente **Linear Discriminant Analysis (LDA)** y **Quadratic Discriminant Analysis (QDA)**.

Ambos métodos se fundamentan en la teoría de los clasificadores bayesianos y asumen que los datos de cada clase provienen de distribuciones normales multivariadas. A partir de esta hipótesis, el problema de clasificación se transforma en la estimación de parámetros estadísticos, como vectores de medias y matrices de covarianza, que permiten calcular la probabilidad de pertenencia de una observación a cada clase.

Además de analizar los fundamentos teóricos de estos modelos, el trabajo se centra en la optimización de sus implementaciones mediante técnicas de álgebra lineal y factorización matricial. Para ello se desarrollan variantes más eficientes de QDA que buscan reducir el costo computacional y el consumo de memoria sin alterar el resultado de las predicciones.

Entre los principales objetivos se encuentran:

* Comprender el funcionamiento matemático de los clasificadores LDA y QDA.
* Implementar distintas variantes optimizadas de los algoritmos propuestos.
* Analizar los pasos algebraicos involucrados en cada transformación.
* Verificar la equivalencia de las predicciones entre las implementaciones optimizadas y las versiones de referencia.
* Comparar desempeño en términos de tiempo de ejecución, uso de memoria y precisión de clasificación.

El desarrollo del trabajo utiliza herramientas de Python para el procesamiento de datos, cálculo matricial y evaluación experimental, permitiendo contrastar el impacto de diferentes estrategias de optimización sobre conjuntos de datos reales.

## Integrantes

* Luis Paredes
* Hernando Santos Scheidl
* Diego Vázquez
* Néstor Biedma

## Contenido del repositorio

* Desarrollo teórico de clasificadores bayesianos.
* Implementaciones de LDA y QDA.
* Versiones optimizadas de QDA mediante técnicas matriciales.
* Comparaciones de rendimiento y exactitud.
* Experimentos y análisis de resultados.


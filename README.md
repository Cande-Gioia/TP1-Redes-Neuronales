# TP1-Redes-Neuronales

## Alumnos:
* Antonin Sibeleau
* Anna Candela Gioia

Objetivo: realizar un bag of words 

Implementación: se tomaron datasets para train y test y se realizó el EDA. Estos datasets fueron 'filtrados' por distintos métodos para reducirlos y no tener datos innecesarios. Luego, se determinaron a través de gráficos los mejores min_df y max_df, es decir, aquellos que maximixan el score, que en este caso es accuracy con dos modelos: Naive Bayes y Regresión Logística. Esto último se realizó a través de cross validation, es decir, se dividió el dataset de train en una parte para probar el modelo. Finalmente, se testeó con test haciendo un grid search con los parámetros de alpha para Naive Bayes y de C para Regresión Logística. 

## Librerías utilizadas:
*sklearn
*numpy
*matplotlib

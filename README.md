# Time_series

En este proyecto se trabaja aprendizaje automático en una serie temporal.

Se trabaja con una serie temporal de pedidos de taxi en aeropuertos. El objetivo es predecir la cantidad de pedidos para la proxima hora, para poder tener las unidades suficientes para el número requerido de viajes.

Para iniciar a analizar series temporales, se hace el remuestreo por el periodo de tiempo que queremos predecir. En este caso, remuestreamos por hora.

Se descompone la serie y se calculan la tendencia, estacionalidad y residuo, así como la diferenciación, para observar el comportamiento de los datos.

Posteriormente, se forma el df, defino una función para crear las caracteristicas para el modelo considerando el max_lag y rolling mean deseados.

Creo 3 modelos para probarlos y encontrar al mejor, modelo lineal, arbol de regresiñon y catboost. Para este proyecto, la regresión lineal resulto en el RECM(raiz de error cuadratico medio) más bajo. Por lo que es el modelo que mejor funciona.

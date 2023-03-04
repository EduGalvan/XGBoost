# XGBoost

En el archivo 'XGBoost and gradient descent' se encuentra una pequeña demo con datos generados artificalmente en la que se intenta comparar la precision con la que ambos modelos predicen los parámetros para un modelo de regresión lienal simple, a la que se le añade un poco de ruido.


En el archivo XGBoost salarios encontramos un dataset de aproximadamente 32.000 individuos en la que se encuentra informacion sobre 14 variables, tanto categoricas como numéricas y una variable objetivo, si los individuos tienen un sueldo anual de +50K $ anuales. También se aáden algunas variables artificiales combinando o haciendo transformaciones de las variables originales para aumentar la cantidad de infromacion del modelo.
En este casso se utiliza un algoritmo de gradient boosting, y se utiliza un algortimo de validación cruzada que nos permite observar cuales son los parámetros mas óptimos para este set de datos.
Con el mejor estimador del modelo se obtiene una precisión del 87,5%

los datos han sido recopilados por la Universidad de california y s epueden encontrar en: https://archive.ics.uci.edu/ml/datasets/adult


En el archivo creditcard, se utiliza un set de datos de gran tamaño 280000 individuos, cuyas variables muy posiblemetne sean una transformación a coordenadas principales de las variables originales para mantener la información sensible de los clientes del banco segura, tambien se encuentra la variable clase, que hace referencia a si los individuos cometen o no fraude con las tarjetas de crédito. Sobre este conjunto de datos, primero utilizamos técnicas de visualización para observar como se diferencian los individuos estafadores (Clase 1), de los no estafadores (Clase 0) en un plano tridimensional interactivo, que se exporta en html para poder manejarlo con mas facilidad. Despues aplicamos un algoritmo de XGBoost, utilizando el Grid Search Cross Validation, para encontrar el mejor set de parámetros que se ajustena  los datos. Finalmente se obtiene un precision del 99,95% de precisión a la hora de predecir si un individuo es un estafador o no.
